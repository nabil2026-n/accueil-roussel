# Fleurs Roussel 🌸

## Présentation du projet

Ce projet consiste à intégrer une maquette Figma en une page web responsive pour **Fleurs Roussel**, une boutique artisanale de fleurs située à Blois.

La page présente les bouquets de la semaine, les avantages de la boutique et les ateliers de composition florale.

## Technologies utilisées

- HTML5
- Tailwind CSS v4
- Google Fonts : Inter et Playfair Display
- npm

## Fonctionnalités

- Mise en page responsive (mobile et desktop).
- Navigation entre les différentes sections.
- Présentation des bouquets et des ateliers.
- États visuels au survol (`hover`) et au focus (`focus-visible`).
- Structure HTML sémantique et accessible.

## Installation

Cloner le dépôt GitHub :

```bash
git clone URL_DU_DEPOT
```

Accéder au dossier du projet :

```bash
cd accueil-roussel
```

Installer les dépendances :

```bash
npm install
```

## Développement

Pour lancer Tailwind CSS en mode surveillance :

```bash
npm run dev
```

## Build

Pour générer le fichier CSS optimisé :

```bash
npm run build
```

Le fichier CSS généré se trouve dans `dist/output.css`.

## Structure du projet

```text
accueil-roussel/
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── src/
│   └── input.css
├── images/
└── dist/
    └── output.css
```

## Auteur

Projet réalisé dans le cadre d'un exercice d'intégration web à partir d'une maquette Figma.

