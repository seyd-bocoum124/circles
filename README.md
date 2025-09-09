# Le jeu *Circles*

## Description

* Description du projet :
**Circles** est un jeu vidéo développé en C avec la bibliothèque graphique **SDL2**. Inspiré du célèbre jeu *Super Hexagon* de Terry Cavanagh, le joueur incarne un triangle bleu qui doit éviter des obstacles rouges se rapprochant du centre d'un disque.  
Le gameplay se concentre sur la précision et les réflexes, offrant une expérience immersive et dynamique.

* Contexte :
Ce projet a été réalisé dans le cadre du cours **[nom du cours, INF3135 - Construction et maintenance de logiciels]**, proposé à l'**[UQAM]**.  
Il s'agit du **troisième travail pratique**, visant à appliquer les concepts de programmation graphique et de développement de jeux vidéo.


## Auteurs

- Seydina Mohamed Bocoum (BOCS92260401)
- Cheikhoul Khadim Diop (DIOC87330308)

## Dépendances

Ce projet nécessite les bibliothèques et outils suivants pour être compilé et exécuté correctement :

### Outils
- **GCC** : Un compilateur pour le langage C 

### Bibliothèques

- **SDL2** : Une bibliothèque pour le développement multimédia.
- **SDL2_image** : Une extension de SDL2 pour la gestion des images (formats PNG, JPEG, etc.).
- **SDL2_mixer** : Une extension de SDL2 pour la gestion des fichiers audio.
- **SDL2_ttf** : Une extension de SDL2 pour le rendu de polices de caractères.
- **SDL2_gfx** : Une extension de SDL2 pour des fonctions graphiques supplémentaires.
- **Mathématiques** : La bibliothèque mathématique standard (`-lm`).

### Installation des dépendances sous Linux (Debian/Ubuntu)

```bash
sudo apt-get install gcc libsdl2-dev libsdl2-image-dev libsdl2-mixer-dev libsdl2-ttf-dev libsdl2-gfx-dev
```



## Fonctionnement

### But du jeu
Le joueur contrôle un **triangle bleu** qui se déplace autour d'un **disque gris** situé au centre de la scène.  
L'objectif est d'éviter les **obstacles rouges**, représentés par des arcs de cercle qui convergent vers le centre.  
- Si, à un moment donné, le **triangle** entre en contact avec un **arc rouge**, le joueur perd et est dirigé vers la page "GAME OVER".

### Contrôles du jeu
- **Flèche gauche** : Déplace le triangle dans le sens **antihoraire** autour du disque.  
- **Flèche droite** : Déplace le triangle dans le sens **horaire** autour du disque.

### Navigation dans le menu
- Utilisez les la souris pour naviguer dans le menu principal.  
- Appuyez sur **Faites un click droit** pour valider une option.

### Compilation
Pour compiler le projet, exécutez la commande suivante :  
```bash
make
```
Pour lancer le jeu, éxécuter l'éxécutable `circles` produit après l'éxécution de la commande make comme suit:
```bash
./circles
```


## Division des tâches

Liste des tâches effectuée:

* [X] Gestion du menu (Khadim)
* [X] Affichage de la scène (Seydina)
* [X] Affichage du chronomètre (Khadim)
* [X] Animation des murs (Khadim)
* [X] Animation du joueur (Seydina)
* [X] Détection des collisions (Seydina)
* [X] Affichage d'une partie terminée (Khadim)
* [X] Gestion de la musique principale (Seydina)
* [X] Gestion des sons lorsqu'on navigue dans le menu (Seydina)
* [X] Gestion de la musique de fin de partie (Khadim)

## État du projet

le projet est complété et sans bogue.
