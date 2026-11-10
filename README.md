# JEANBAR COSMIQUE — MVP 0.1

Site éditorial expérimental Astro statique, prêt pour GitHub Pages.

## Lancer localement

Prérequis : Node.js 22+ et npm.

```bash
npm install
npm run dev
```

Ouvrir l'URL locale indiquée par Astro (généralement http://localhost:4321/jeanbar-cosmique/).

## Personnaliser

- `src/lib/data.mjs` : contenus de démonstration des Jeanpapelars et du laboratoire.
- `src/pages/` : rubriques et pages.
- `src/styles/global.css` : palette, typographie, responsive.
- `src/layouts/Base.astro` : navigation et pied de page.

**Attention** : les textes fournis sont des exemples éditoriaux ; ils ne représentent pas des résultats de recherche validés. Les relire avant publication.

## Publier gratuitement sur GitHub Pages

1. Créer un dépôt public GitHub nommé `jeanbar-cosmique`.
2. Copier le projet dans ce dépôt.
3. Le workflow installe les dépendances lors du déploiement. Pour figer les versions, exécuter `npm install` en local et commiter ensuite `package-lock.json`.
4. Pousser la branche `main` : `git add . && git commit -m "Initial JEANBAR MVP" && git push -u origin main` (après création du remote).
5. Dans `Settings > Pages > Build and deployment > Source`, choisir `GitHub Actions`.
6. L'action incluse publie le site à `https://VOTRE-UTILISATEUR.github.io/jeanbar-cosmique/`.

L'environnement GitHub Actions donne automatiquement le propriétaire et le dépôt à `astro.config.mjs`. Pour un déploiement local à la racine, vous pouvez définir `GITHUB_PAGES_BASE=/`.

## Limitations

- Pas de back-end, comptes, commentaires ou stockage utilisateur.
- Pas de génération automatisée des citations ni système de validation probatoire.
- Carte de constellations illustrative/statique.
- Données de démonstration dans un module JavaScript simple ; migration possible ensuite vers Astro Content Collections Markdown.
- Les polices Google sont chargées en ligne ; des polices de remplacement locales sont utilisées hors ligne.
- Dépôt public requis sur GitHub Free pour GitHub Pages.

## Statut

MVP technique non déployé. Les contenus sont fictifs ou illustratifs, à approuver avant publication.
