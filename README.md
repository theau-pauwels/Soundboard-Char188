# Soundboard Char 188

Soundboard Astro statique utilisant les voicelines présentes dans ce dépôt.

## Développement

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Le résultat statique est généré dans `dist/`.

## Déploiement Vercel

Importe simplement ce dépôt dans Vercel. Le projet est un site Astro statique : aucun adapter Vercel ni variable d'environnement n'est nécessaire.

Les fichiers audio restent à la racine du dépôt et sont lus depuis leur URL GitHub brute afin d'éviter de dupliquer les médias.
