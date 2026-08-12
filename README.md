# Twirling Passion Paquelaisienne

[![HTML5](https://img.shields.io/badge/HTML5-Markup-E34F26?logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)]()
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.1.3-7952B3?logo=bootstrap&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Completed-success)]()

---

## Description

**Twirling Passion Paquelaisienne** est un site vitrine fictif réalisé dans un cadre pédagogique pour une association sportive de twirling.

Le projet présente l'association, ses actualités, sa galerie photos ainsi que ses différents événements.

Initialement développé comme projet d'apprentissage, le site a ensuite fait l'objet d'une modernisation complète de son interface et de son responsive design afin d'améliorer sa présentation, sa maintenabilité et son intégration dans un portfolio de développeur web.

---

## Fonctionnalités

### Frontend

- Présentation de l'association
- Navigation responsive avec Bootstrap
- Section d'actualités sous forme d'accordéon
- Galerie photos avec carousel Bootstrap
- Affichage responsive des images sans déformation
- Page dédiée aux événements
- Mise en avant du prochain événement
- Présentation des événements à venir
- Formulaire de contact et de participation
- Liens vers les réseaux sociaux
- Design responsive pour desktop, tablette et mobile
- Interface modernisée avec cartes, ombres, animations et effets au survol

### Formulaire  


Le formulaire de la page événements est préparé pour fonctionner avec Netlify Forms lors d'un déploiement compatible.

Il permet notamment de renseigner :

- Nom et prénom
- Adresse e-mail
- Téléphone
- Type de demande
- Message
- Consentement à l'utilisation des informations transmises

---  

## Stack technique

- HTML5
- CSS3
- JavaScript ES6+
- Bootstrap 5.1.3
- Flexbox
- CSS Grid
- Responsive Design
- Git
- GitHub

---

## Installation

### Prérequis

Le projet est entièrement statique.

Aucune installation de dépendances n'est nécessaire.

Un navigateur web moderne suffit pour l'utiliser.

---

### Étapes

#### 1. Cloner le projet

```bash
git clone https://github.com/DdLgc/Twirling-Paquelaisienne.git
```

#### 2. Accéder au projet

```bash
cd Twirling-Paquelaisienne
```

#### 3. Lancer le projet

Le projet ne nécessite aucune compilation.

Vous pouvez ouvrir directement :

```text
index.html
```

dans votre navigateur.

Pour le développement local, il est également possible d'utiliser un serveur local tel que :

- Live Server
- WAMP
- XAMPP
- Apache

---

## Utilisation

La page d'accueil permet de découvrir l'association ainsi que les dernières actualités du club.

La navigation donne ensuite accès aux différentes parties du site :

- **Accueil** — présentation et actualités du club
- **Photos** — galerie photos interactive
- **Événements** — événements à venir et formulaire de participation
- **Contact** — accès rapide aux informations de contact depuis le footer

Le site est conçu pour fonctionner sur ordinateur, tablette et smartphone.

---

## Modernisation du projet

Ce projet étant issu d'un ancien exercice de formation, une phase de refactorisation et de modernisation a été réalisée.

### Galerie

- Correction du carousel Bootstrap
- Correction des contrôles précédent / suivant
- Suppression des dimensions forcées sur les images
- Utilisation de `object-fit`
- Conservation du ratio des photographies
- Adaptation de la galerie aux différentes tailles d'écran

### Page d'accueil

- Refonte de la présentation de l'association
- Nouvelle mise en page avec Flexbox et CSS Grid
- Modernisation des cartes
- Refonte de la section actualités
- Ajout d'actualités fictives pour compléter la démonstration
- Correction des accordéons Bootstrap
- Amélioration de la hiérarchie visuelle

### Événements

- Refonte complète de la page
- Mise en avant d'un événement principal
- Ajout d'événements fictifs à venir
- Nouveau formulaire de participation
- Suppression des anciennes structures HTML invalides
- Préparation du formulaire pour Netlify Forms

### Responsive Design

- Simplification des media queries
- Suppression des anciens breakpoints inutiles
- Amélioration de l'affichage mobile
- Navigation responsive
- Cartes adaptatives
- Images non déformées

### Structure générale

- Mise en place d'une structure `<main>`
- Correction du positionnement du footer
- Amélioration de la sémantique HTML
- Nettoyage du CSS historique
- Harmonisation graphique des différentes pages

---

## Compétences développées

- Structuration sémantique HTML5
- Mise en page avec Flexbox et CSS Grid
- Responsive Web Design
- Utilisation et personnalisation de Bootstrap
- Gestion d'un carousel
- Création d'accordéons interactifs
- Création et structuration de formulaires
- Refactorisation d'un ancien projet
- Correction de code HTML/CSS existant
- Maintenance et amélioration progressive d'une interface
- Git & GitHub
- Workflow professionnel

---

## Workflow Git

Le projet utilise un workflow basé sur des branches dédiées aux différentes évolutions.

Branches utilisées lors de la modernisation :

```text
main
│
├── fix/gallery-carousel
├── fix/layout-footer
├── style/homepage-modernization
└── style/event-page-modernization
```

Types de branches utilisés :

- `fix/*` — corrections
- `style/*` — améliorations visuelles
- `docs/*` — documentation
- `refactor/*` — refactorisation éventuelle

### Conventional Commits

Le projet utilise une convention de commits lisible :

```text
feat:
fix:
docs:
refactor:
style:
chore:
```

Exemples :

```text
fix: improve gallery carousel and image display
fix: improve page layout and footer positioning
style: modernize homepage layout and news section
style: modernize events page and registration form
```

---

## Améliorations possibles

Le projet est considéré comme **terminé dans le cadre de son objectif pédagogique**, mais plusieurs évolutions resteraient possibles :

- Connecter le formulaire à un véritable système de traitement côté serveur
- Administrer dynamiquement les événements et actualités
- Charger la galerie depuis une API ou un CMS
- Ajouter des animations d'apparition
- Optimiser davantage les images
- Ajouter des tests automatisés
- Migrer certaines ressources externes vers des fichiers locaux

Ces améliorations ne sont pas nécessaires pour la version actuelle du projet.

---

## 🔗 Links

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ddlgc-portfolio.netlify.app/)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DdLgc/Twirling-Paquelaisienne)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-le-gouellec-551322243/)

---

## Arborescence

```text
Twirling-Paquelaisienne/
│
├── img/
│   ├── article.jpg
│   ├── article1.jpg
│   ├── articlee.jpg
│   ├── articlee1.jpg
│   ├── carte.png
│   ├── croissant.jpg
│   ├── entete.jpeg
│   ├── fondarticle.jpg
│   ├── fonddecran.jpg
│   ├── gala19.JPG
│   ├── gala 20-21.JPG
│   ├── logo sans fond.png
│   ├── loto.png
│   ├── photoprofil.jpg
│   ├── photo10fev.jpg
│   └── ...
│
├── event.html
├── index.html
├── photos.html
├── script.js
├── style.css
└── README.md
```

> Le dossier `img/` contient l'ensemble des photographies, illustrations, logos et icônes utilisés par le site.

---

## Captures d'écran

À venir.

---

## Auteur

**David Le Gouellec**

Développeur web en formation, ce projet fait partie de mes réalisations pédagogiques et illustre notamment mon travail de reprise, de refactorisation et de modernisation d'une application frontend existante.

---

## Licence

Projet réalisé à des fins pédagogiques.

Vous êtes libre de le consulter, de l'utiliser et de l'adapter pour votre apprentissage.  
(Autres dépot pouvant aidé pour un workflow, commits, branch... bien structuré 
[GitHub](https://github.com/DdLgc/DdLgc-Development_Standards) DdLgc-Development_Standards)