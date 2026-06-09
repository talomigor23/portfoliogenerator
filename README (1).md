# Portfolio Generator

> Créez un portfolio web élégant en quelques clics, puis exportez-le en un fichier HTML autonome, prêt à héberger gratuitement.

Un petit outil open source, **100 % local** (aucun serveur, aucune donnée envoyée nulle part) : on remplit un formulaire, on choisit un modèle et une animation, on voit l'aperçu en direct, et on télécharge un site `.html` complet à mettre en ligne où l'on veut.

🔗 **Démo en ligne :** https://talomigor23.github.io/portfoliogenerator/

<!-- Astuce : ajoute une capture d'écran ici, par ex. ![Aperçu](docs/preview.png) -->

## ✨ Fonctionnalités

- **21 modèles** au choix : Minimal, Signature, Split, Showcase, Bento, Aurora, Éditorial, Terminal, CV, Néon, Sérénité, Brut, Studio, Architecte, Galerie, Mode, Carte, Corporate, Emily, Daniel, Ashley.
- **Aperçu en temps réel** avec bascule **vue bureau / vue mobile** (rendu type émulateur de téléphone).
- **7 animations d'apparition au défilement** : Fondu, Montée, Zoom, Flou, Glissé, Bascule, Ressort (plus « Aucune »).
- **Personnalisation poussée** : 19 palettes + couleurs sur mesure (clair/sombre), 3 familles de police, 5 fonds/textures.
- **Recadrage d'image intégré** (zoom, déplacement) pour la photo de profil et les visuels de projet.
- **Réseaux sociaux en icônes** : email, téléphone, WhatsApp, Instagram, TikTok, GitHub, LinkedIn, site web.
- **Sections complètes** : profil, contact, compétences, projets, expériences, parcours académique, certifications (avec justificatif image ou PDF intégré au site).
- **Réordonnancement des sections** par glisser-déposer (ou flèches).
- **Sauvegarde automatique** dans le navigateur (IndexedDB) + **export / import** du projet au format `.json`.
- **Thème d'interface** clair ou sombre.
- **Export en HTML autonome** : images, PDF et contenu inclus dans un seul fichier, sans dépendance.

## 🚀 Utilisation

1. Ouvre l'outil ([démo en ligne](https://talomigor23.github.io/portfoliogenerator/) ou ton propre `index.html`).
2. Remplis les sections (profil, projets, expériences…) — tout s'enregistre automatiquement.
3. Choisis un **modèle**, une **palette** et une **animation** ; l'aperçu se met à jour en direct.
4. Clique sur **« Télécharger le HTML »** pour obtenir `ton-nom.html`.
5. Héberge ce fichier où tu veux (voir ci-dessous).

## 🌍 Mettre ton portfolio en ligne

Le fichier exporté est un site statique autonome. Quelques options gratuites :

- **GitHub Pages** : crée un dépôt, dépose ton fichier en le renommant `index.html`, puis active Pages (voir plus bas).
- **Netlify** : glisse-dépose le fichier sur [app.netlify.com/drop](https://app.netlify.com/drop).
- **Vercel** : importe le fichier depuis un dépôt Git.

## 🛠️ Lancer le projet en local

Aucune installation, aucune dépendance. Clone le dépôt et ouvre le fichier :

```bash
git clone https://github.com/talomigor23/portfoliogenerator.git
cd portfoliogenerator
# puis ouvre index.html dans ton navigateur (double-clic), ou :
python3 -m http.server 8000   # http://localhost:8000
```

## ☁️ Publier l'outil lui-même (GitHub Pages)

`index.html` est déjà à la racine du dépôt, donc la mise en ligne tient en quelques clics :

1. Dépôt → **Settings** → **Pages**.
2. **Build and deployment → Source** : *Deploy from a branch*.
3. **Branch** : `main`, dossier `/ (root)` → **Save**.
4. Après une minute, le site est servi sur `https://talomigor23.github.io/portfoliogenerator/`.

## 🧱 Stack technique

HTML, CSS et JavaScript natifs (« vanilla »), un seul fichier, **sans framework ni dépendance externe**. Stockage local via IndexedDB. Les icônes de marque proviennent de [Simple Icons](https://simpleicons.org).

## 🤝 Contribuer

Les retours, idées et pull requests sont les bienvenus — c'est un projet fait pour le plaisir. Ouvre une *issue* pour signaler un bug ou proposer un modèle/une fonctionnalité.

## 📄 Licence

Distribué sous licence [MIT](LICENSE). Tu es libre de l'utiliser, le modifier et le partager.

## 👤 Auteur

**Tuedom Talom Igor** — [@talomigor23](https://github.com/talomigor23)
