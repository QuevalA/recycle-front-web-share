# reCycle

## Table des matières
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Principales dépendances](#principales-dépendances)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Contributeurs](#contributeurs)

<br>

## Introduction
**reCycle** est une plateforme permettant aux utilisateurs d’échanger des biens et services sans impliquer d’argent.
De cette manière, ils peuvent donner une seconde vie à des objets dont ils n’ont plus besoin, et ceux qui n’en ont pas à distribuer peuvent toujours s’impliquer en proposant leurs compétences à travers des services.
Cette application est grandement inspirée de Leboncoin et Geev.

Un système de points a été pensé pour équilibrer les échanges, garantissant que plus vous donnez, plus vous êtes en mesure de recevoir. Chaque utilisateur a un profil public qui affiche son expérience dans l’application, incluant sa date d’inscription et le nombre de transactions qu’il a conclu avec succès.

Du point de vue technique, reCycle est basée sur un back-end Symfony servant d’API à des interfaces web en React.js (publique et back-office) et une interface mobile en React native. L'API REST est sécurisée par JWT.

**Ce dépôt contient la partie front end du projet.**

Partie back end : https://github.com/QuevalA/recycle-back-share
<br>Partie mobile : https://github.com/QuevalA/recycle-front-mobile-share
<br>Partie back office : https://github.com/QuevalA/recycle-back-office-share

<br>

## Technologies

- **React** : Une bibliothèque JavaScript pour créer des interfaces utilisateur.
- **Create React App** : Un environnement de configuration pour démarrer rapidement avec React.
- **Tailwind CSS** : Un framework de style CSS utilitaire.
- **Multer** : Un middleware Node.js pour le traitement de fichiers multipart/form-data.
- **Axios** : Une bibliothèque pour faire des requêtes HTTP depuis le navigateur.
- **React Router** : Une bibliothèque pour la gestion des routes dans les applications React.

<br>

## Principales dépendances

- react : ^18.2.0
- react-dom : ^18.2.0
- react-router-dom : ^6.3.0
- axios : ^1.2.1
- jwt-decode : ^3.1.2
- react-dropzone : ^14.2.3
- react-loader-spinner : ^5.3.4
- multer : ^1.4.5-lts.1
- @cloudinary/react : ^1.11.2
- @cloudinary/url-gen : ^1.10.1
- uuid : ^9.0.0

<br>

## Prérequis
Avant de commencer l'installation et l'utilisation de ce projet, assurez-vous que votre environnement répond aux prérequis suivants :

- **Node.js**: (version 14 ou plus) Vous pouvez le télécharger depuis nodejs.org.
- **npm**: (inclus avec Node.js) : Utilisé pour gérer les dépendances JavaScript.
- **Git**: Pour cloner le dépôt du projet. Téléchargez-le depuis git-scm.com.

<br>

## Installation
1. Cloner le projet en local.
2. Installez les dépendances : `npm install`
3. Installez les dépendances : `npm start`
4. Ouvrez http://localhost:3000 pour voir l'application dans votre navigateur. La page se rechargera automatiquement si vous apportez des modifications au code source.

<br>

## Contributeurs
Kévin Terrier, Curtis Marty-Jackson, Alexis Carrere, Adam Queval.