# Hangman Web - Documentation

Ce projet Hangman Web a été entretenu par Luka GARCIA, Thomas WEBER et Pierre-Hervé POIRIER.

## Sommaire

- [I. A propos du projet](#i-a-propos-du-projet)
- [II. Utilisation de Hangman Web](#ii-utilisation-de-hangman-web)
- [III. Réalisation des consignes & bonus](#iii-réalisation-des-consignes-bonus)
    - [A. Consignes requises](#a-consignes-requises)
    - [B. Bonus 1 : level](#b-bonus-1-level)
    - [C. Bonus 2 : gamify](#c-bonus-2-gamify)
    - [D. Bonus 3 : bring-to-death](#d-bonus-3-bring-to-death)
- [IV. Crédits](#iv-crédits)


## I. A propos du projet

Le projet Hangman Web est un projet dont le but est de recréer le jeu du pendu sur une interface web en utilisant un langage imposé : le [Golang](https://go.dev/).

Nous avons choisi de suivre la charte graphique de Ytrack, la plateforme de gestion de projets d'Ynov, mélée à une idée de terminal, pour rappeler notre ancien projet [hangman](https://github.com/LukaGrc/Hangman).

## II. Utilisation de Hangman Web

Pour lancer le projet, vous avez seulement besoin de cloner ou télécharger ce repository, ouvrir un terminal et vous diriger dans le dossier contenant le projet.
Ici, vous n'avez plus qu'à exécuter la commande `go run main.go`, et utiliser votre navigateur pour vous rendre sur le lien suivant : [http://localhost:8080](http://localhost:8080).

## III. Réalisation des consignes & bonus

### A. Consignes requises

La consigne principale était de créer une interface web proposant de jouer au jeu du pendu avec le langage de programmation Golang.

---

### B. Bonus 1 : level

Le bonus "level" consiste dans l'ajout d'un choix de difficulté avant de commencer une partie : il nous est demandé d'implémenter une page dédiée au début de la partie qui permet à l'utilisateur de choisir entre trois difficultés (EASY / MEDIUM / HARD).

---

### C. Bonus 2 : gamify

Le bonus "gamify" consiste à faire en sorte que l'interface corresponde mieux à un jeu vidéo.

Il nous a donc été demandé de créer de nouvelles interfaces telles que : une page de connexion (pour choisir son pseudo), un écran de fin de partie (gagné / perdu), un bouton pour jouer de nouveau, un scoreboard, une liste des lettes déjà utilisées durant la partie, ...

---

### D. Bonus 3 : bring-to-death

Le bonus "bring-to-death" consiste en la création d'un pendu qui s'actualise au fur-et-à-mesure du jeu, afin de rendre plus visuel le nombre d'essais restants.

Chaque fois que l'on émet une suggestion mauvaise (mauvaise lettre / mauvais mot), le pendu apparaît de plus en plus.

## IV. Crédits

Le projet Hangman Web a été conçu par Luka GARCIA, Thomas WEBER et Pierre-Hervé POIRIER (avec l'aide précieuse des mentors qui nous ont accompagnés).
