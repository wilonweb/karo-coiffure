# Karo Coiffure

Site vitrine one-page pour **Karo Coiffure**, salon de coiffure mixte à La Ciotat.

## Stack

- [AstroJS](https://astro.build) — framework statique, pas de JS framework additionnel
- CSS vanilla avec variables custom
- Google Fonts — Space Grotesk
- GitHub Pages — déploiement automatique via GitHub Actions

## URL de production

**https://wilonweb.github.io/karo-coiffure/**

## Lancer en local

```bash
npm install
npx astro dev --background   # démarre sur http://localhost:4321
npx astro dev stop           # arrête le serveur
npx astro dev logs           # voir les logs
```

## Build

```bash
npm run build   # génère ./dist/
```

## Structure

```
src/
├── pages/
│   └── index.astro     # page unique (toutes les sections)
└── styles/
    └── global.css      # variables, reset, utilitaires
```

## Déploiement

Chaque push sur `main` déclenche GitHub Actions → build Astro → deploy sur GitHub Pages.
Voir l'avancement : https://github.com/wilonweb/karo-coiffure/actions
