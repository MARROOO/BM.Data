# Portfolio — Mariem Bjaoui

Site one-page, autonome (HTML/CSS/JS, sans dépendance de build), prêt à héberger.

## Structure du dossier

```
index.html
assets/
  img/portrait.jpg          (photo de profil)
  cv/CV_Mariem_BJAOUI.pdf   (CV téléchargeable depuis le site)
```

Important : conservez cette structure exacte (le fichier `index.html` doit rester au même niveau que le dossier `assets/`), sinon la photo et le bouton « Télécharger le CV » ne fonctionneront plus.

## Héberger le site (3 options gratuites)

**Netlify (le plus simple)**
Aller sur netlify.com, glisser-déposer le dossier complet (avec `assets/`) sur la zone de dépôt. Le site est en ligne en quelques secondes, avec une URL du type `votre-nom.netlify.app`. Possibilité ensuite de connecter un nom de domaine personnalisé dans les réglages.

**GitHub Pages**
Créer un dépôt GitHub, y pousser ces fichiers, puis activer GitHub Pages dans Settings → Pages en choisissant la branche `main`. Le site sera accessible à `votre-pseudo.github.io/nom-du-depot`.

**Vercel**
Créer un compte sur vercel.com, importer le dossier (ou un dépôt GitHub), déployer. URL fournie automatiquement.

Dans les trois cas, aucune configuration serveur n'est nécessaire : c'est un site statique.

## Personnalisation rapide

Les couleurs, polices et textes sont centralisés en haut du fichier `index.html` (section `:root` pour les couleurs). Le contenu de chaque section est dans le `<body>`, en français, facilement repérable par les titres `<h2>`.

## À vérifier avant publication

La section « RIMOWA — Groupe LVMH » contient une description de poste rédigée à titre de proposition (basée sur un stage e-commerce data analyst type chez RIMOWA). Avant de mettre le site en ligne, relisez et ajustez ces missions pour qu'elles correspondent précisément à vos tâches et réalisations réelles.
