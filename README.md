# Gestion de Recettes

## Introduction

Bienvenue dans le projet de Gestion de Recettes ! Cette application permet aux utilisateurs de gérer leurs recettes de cuisine de manière simple et intuitive. Le projet utilise Vue.js 3 avec la Composition API, Pinia pour la gestion des états globaux, et Bootstrap pour le design de l'interface utilisateur.

## Fonctionnalités Principales

1. **Ajout de Recettes** :

   - Les utilisateurs peuvent ajouter de nouvelles recettes avec des informations telles que le titre, les ingrédients, et le type (entrée, plat, dessert, etc.).

2. **Modification de Recettes** :

   - Les recettes ajoutées peuvent être modifiées par les utilisateurs.

3. **Suppression de Recettes** :

   - Les utilisateurs peuvent supprimer des recettes.

4. **Affichage de la Liste des Recettes** :
   - Une page dédiée permet de visualiser toutes les recettes disponibles et de voir les détails d'une recette spécifique.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants :

- Node.js (version 16 ou supérieure recommandée)
- npm (ou yarn) installé

## Technologies utilisées

- Vue.js 3: Framework JavaScript pour la création d'interfaces utilisateur.
- Composition API: Nouveau système de composition de composants dans Vue 3.
- Pinia: Store d'état global pour Vue.js.
- Bootstrap: Framework CSS pour le style.

## Installation

1. Clonez le dépôt :

```bash
    git clone https://github.com/Mohamed11abdallah/api_recette_frontend.git
```

2. Accédez au répertoire du projet :

```bash
    cd api_recette_frontend
```

Installez les dépendances :

`npm install`

## Démarrer le projet

Pour démarrer l'application en mode développement, utilisez la commande suivante :

`npm run dev`

## Utilisation d'Axios

- L'application de gestion de recettes utilise Axios pour faciliter les échanges avec le serveur backend. Grâce à cela, elle peut effectuer des opérations telles que récupérer, ajouter, modifier et supprimer des recettes et des catégories en envoyant des requêtes HTTP au serveur.

## Gestion de la Traduction (i18n)

- L'application gère le multilinguisme en utilisant i18n pour assurer la traduction des contenus. Cela permet aux utilisateurs de basculer entre différentes langues en temps réel. Les textes de l'interface se mettent à jour instantanément, offrant une expérience utilisateur adaptée à la langue choisie, tout en appliquant des traductions par défaut lorsque certaines ne sont pas disponibles.

## Auteur

[Mohamed Abdallahi M'khaitir](https://github.com/Mohamed11abdallah)
