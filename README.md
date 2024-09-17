# Intégration de l'interface visuelle et responsive avec HTML et CSS

## Sommaire

* [Description](#description)
* [Fonctionnalités](#fonctionnalités)
* [Installation](#installation)
* [Structure du projet](#structure-du-projet)
* [Technologies utilisées](#technologies-utilisées)
* [Note de synthèse](#note-de-synthèse)
  * [Spécifications fonctionnelles](#spécifications-fonctionnelles)
  * [Spécifications techniques](#spécifications-techniques)
* [Screenshots](#screenshots)
* [Auteur](#auteur)

## Description

Ce projet consiste à intégrer une maquette pour un site web de réservation d'hébergements et d'activités pour la startup Booki. Le site doit être responsive et permettre aux utilisateurs de rechercher des logements ou des activités dans la ville de leur choix.

L'objectif est d'intégrer la maquette fournie avec du code HTML et CSS, en respectant les consignes et contraintes techniques spécifiées. 

Ce projet fait partie de ma formation sur OpenClassrooms pour le parcours [Développeur Web](https://openclassrooms.com/fr/paths/899-developpeur-web).

## Fonctionnalités

- Affichage des hébergements disponibles dans une ville donnée
- Affichage des activités touristiques à faire dans cette ville
- Interface entièrement responsive, adaptée aux écrans desktop, tablette et mobile

## Installation
1. Clonez le repository :
   ```bash
   git clone https://github.com/MaelleN95/OC-Projet2.git
2. Ouvrez le fichier index.html dans votre navigateur.

## Structure du projet
- `index.html` : Le fichier HTML principal
- `css/style.css` : Le fichier CSS principal
- `images/` : Contient les images utilisées pour la mise en page

## Technologies utilisées
- HTML5
- CSS3
- Git et GitHub pour le versionnement du code

## Note de synthèse

### Spécifications fonctionnelles

| Fonction                      | Description                                                                                                                 |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Fonction recherche**         | - Les usagers pourront rechercher des hébergements dans la ville de leur choix.                                             |
|                               | - Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur.                     |
|                               | - Il faut englober ce champ dans un formulaire. La partie *Recherche* ne doit pas être fonctionnelle.                           |
| **Liens "Hébergements" et "Activités"** | - Les textes “Hébergements” et “Activités” dans l’en-tête sont des liens qui mènent aux sections correspondantes sur la page.    |
| **Cartes hébergements et activités** | - Chaque carte (hébergement ou activité) doit être entièrement cliquable.                                                 |
|                               | - Les liens doivent être simulés avec `href="#"`.                                                                            |
| **Filtres de recherche**       | - Les hébergements peuvent être filtrés par thématique (budget, ambiance, etc.).                                             |
|                               | - Les filtres doivent changer de couleur au survol de la souris.                                                             |
|                               | - Les filtres ne sont pas fonctionnels dans cette version, ils valident simplement l'interface.                              |

### Spécifications techniques

| Thème                          | Informations techniques                                                                                                     |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Maquettes**                   | [Lien vers la maquette](https://www.figma.com/design/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)). Trois maquettes sont disponibles : desktop, tablette et mobile.                                                   |
| **Breakpoints**                 | Utiliser les breakpoints suivants :                                                                                         |
|                                 | - >1024 px pour les écrans d’ordinateurs                                                                                     |
|                                 | - >=768 px pour les tablettes                                                                                                |
|                                 | - <768 px pour les téléphones portables                                                                                      |
| **Largeur min - max**           | - Largeur maximum : 1440 px (au-delà, ajouter des marges blanches).                                                          |
|                                 | - Largeur minimum : 320 px                                                                                                  |
| **Desktop first**               | - L'intégration doit être faite en desktop first, puis adaptée pour les tablettes et les mobiles via des media queries.      |
| **Bibliothèque d’icônes**       | Utilisation de [Font Awesome](https://docs.fontawesome.com/web/setup/get-started) pour les icônes.                                                                                 |
| **Couleurs**                    | - Bleu : `#0065FC`                                                                                                          |
|                                 | - Bleu clair : `#DEEBFF`                                                                                                    |
|                                 | - Gris : `#F2F2F2` (pour le fond)                                                                                           |
| **Police**                      | La police utilisée est Raleway, importée via [ Google Fonts](https://fonts.google.com/specimen/Raleway).|
| **Mise en page**                | Il est recommandé d'utiliser Flexbox pour la mise en page.                                                                   |
| **Balises sémantiques**         | Utiliser les balises sémantiques comme : `header`, `nav`, `h1-h3`, `main`, `section`, `article`, et `footer`.               |
| **Validité du code**            | - Le code doit être valide selon les validateurs W3C (HTML et CSS).                                                          |
|                                 | - Ne pas dupliquer de code HTML entre les versions desktop, mobile et tablette.                                              |
|                                 | - Utiliser les classes CSS plutôt que les noms d'éléments pour le style.                                                    |
| **Compatibilité navigateurs**   | Le site doit être compatible avec les dernières versions de Chrome et Firefox.                                               |
| **Restrictions**                | - Aucun framework CSS (Bootstrap, Tailwind, etc.) ne doit être utilisé.                                                      |
|                                 | - Aucun préprocesseur CSS (Sass, Less, etc.) ne doit être utilisé.                                                           |
|                                 | - Aucun autre langage comme JavaScript ne doit être utilisé.                                                                 |

## Screenshots
### Desktop
![booki-2](https://github.com/user-attachments/assets/6dfe7a0b-88db-4725-9455-32088c0caf24)
### Tablette
![booki-1](https://github.com/user-attachments/assets/4254eb4c-46e1-4378-bda6-27911531abbe)
### Mobile
![booki-3](https://github.com/user-attachments/assets/828d49d5-a473-4534-a7f7-9f1e161ac2fb)

## Auteur

- [Maëlle Nioche](https://www.linkedin.com/in/maelle-nioche/)
