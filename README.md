# Herbiers - Application de gestion de relevés et de lieux

## Description

Herbiers est une application Symfony permettant de gérer des relevés associés à des lieux. Elle offre des fonctionnalités telles que l'ajout, la modification, la suppression, la visualisation et la génération de tableaux pour chaque relevé.

## Fonctionnalités

1. **Gestion des Lieux :** Permet d'afficher, ajouter, modifier et supprimer des lieux.

2. **Gestion des Relevés :** Permet d'afficher, ajouter, modifier et supprimer des relevés.

3. **Tableaux et Visualisations :** Possibilité de générer des tableaux et des visualisations à partir des relevés.

## Installation

1. Clonez le repository.
   ```bash
   git clone https://github.com/votre-utilisateur/herbiers.git
   ```
2. Installez les dépendances.
   ```bash
   composer install
   ```
3. Configurez votre base de données dans le fichier .env.
4. Appliquez les migrations.
   ```bash
   php bin/console doctrine:migrations:migrate
   ```

## Utilisation
- Accédez à la liste des lieux et relevés depuis l'interface principale.
- Ajoutez, modifiez ou supprimez des lieux et relevés selon vos besoins.
- Explorez les fonctionnalités avancées telles que la génération de tableaux et de visualisations.

## Auteur 
Paul SUPIOT
