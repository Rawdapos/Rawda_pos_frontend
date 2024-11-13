# Acme Dashboard

Bienvenue dans le projet Acme Dashboard. Ce projet est un exemple pour le [cours Next.js Learn](https://nextjs.org/learn/), proposé par Vercel.

## Description

Acme Dashboard est une application de tableau de bord construite avec Next.js et Tailwind CSS. Elle permet de gérer les clients et les factures.

## Installation

Pour installer les dépendances du projet, exécutez la commande suivante :

```sh
npm install
```

## Utilisation

### Développement

Pour démarrer le serveur de développement, exécutez :

```sh 
npm run dev 
```

### Production

Pour construire le projet pour la production, exécutez :

```sh
npm run build
```

Pour démarrer le serveur en mode production, exécutez :

```sh
npm run start
```

## Structure du projet

Le projet est organisé comme suit :

## Scripts

Voici les scripts disponibles dans ce projet :

- build: Compile le projet avec Next.js.
- dev: Démarre le serveur de développement.
- lint: Lint le code source.
- prettier: Formate le code source avec Prettier.
- prettier:check: Vérifie le formatage du code source avec Prettier.
- start: Démarre le serveur de production.
- test: Lance les tests end-to-end avec Playwright.

Pour exécuter un script, utilisez la commande suivante :

```sh 
npm run <script>
```

Par exemple, pour démarrer le serveur de développement :

```sh
npm run dev
```

## Configuration

### Playwright

Le fichier de configuration Playwright se trouve dans playwright.config.ts. Il configure le serveur web pour les tests end-to-end.

### TypeScript

Le fichier de configuration TypeScript se trouve dans tsconfig.json. Il définit les options du compilateur TypeScript.

### Tailwind CSS

Le fichier de configuration Tailwind CSS se trouve dans tailwind.config.ts.

### Next.js

Le fichier de configuration Next.js se trouve dans next.config.mjs.

## Tests

Pour exécuter les tests, utilisez la commande suivante :

```sh
npm run test
```

## Contribuer

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

1. Forkez le dépôt.
2. Créez une branche pour votre fonctionnalité (git checkout -b feature/ma-fonctionnalité).
3. Commitez vos modifications (git commit -m 'Ajoute ma fonctionnalité').
4. Poussez votre branche (git push origin feature/ma-fonctionnalité).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
