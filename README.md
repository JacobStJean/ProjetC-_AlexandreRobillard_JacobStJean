# Garage de rêve

## Description du projet

Mon projet est une application WinUI qui permet de créer des collections de voitures. L’utilisateur pourra ajouter les voitures qui l’intéressent, consulter leurs caractéristiques et les classer dans des collections, comme « Voitures classiques » ou « Mon garage idéal ».

## Fonctionnalités prévues

- Ajouter, modifier et supprimer une voiture.
- Entrer la marque, le modèle, l’année et le prix estimé d’une voiture.
- Consulter et modifier sa fiche technique : puissance, vitesse maximale et motorisation.
- Ajouter des marques et afficher leurs voitures.
- Créer, modifier et supprimer des collections.
- Ajouter ou retirer des voitures d’une collection.
- Sauvegarder les informations dans une base de données.

## Classes et relations

L’application contiendra quatre classes principales : `Voiture`, `Marque`, `FicheTechnique` et `Collection`.

- Un à un : chaque voiture possède une fiche technique qui lui appartient.
- Un à plusieurs : une marque peut avoir plusieurs voitures, mais chaque voiture appartient à une seule marque.
- Plusieurs à plusieurs : une collection peut contenir plusieurs voitures et une voiture peut faire partie de plusieurs collections.

## Interface

L’application aura une page pour afficher les voitures, un formulaire pour les ajouter ou les modifier et une page pour gérer les collections.

