# README - Darkest Night V 1.0

 

Ce référentiel contient un jeu d'aventure textuel basé sur Python. Dans ce jeu, les joueurs exploreront différents lieux, rencontreront divers événements 
et se lanceront dans des combats contre des ennemis. Le jeu est basé sur l'entrée de l'utilisateur, et les joueurs font des choix pour naviguer à travers l'histoire.

## Pour Commencer
Pour jouer au jeu, assurez-vous d'avoir Python installé sur votre ordinateur. Vous pouvez télécharger Python depuis le site officiel 
(https://www.python.org/downloads/). Une fois que Python est installé, suivez les étapes ci-dessous pour exécuter le jeu :


1. Clonez ce référentiel sur votre machine locale en utilisant la commande suivante :
   ```
   git clone <repository-url>
   ```
2. Accédez au répertoire du projet contenant les fichiers du jeu.

3. Lancez le jeu en exécutant le script `main.py` :
   ```
   python main.py
   ```


## Déroulement du Jeu

1. **Création d'un Personnage Joueur**
   - Au début du jeu, on vous demandera de saisir votre nom et de choisir un rôle pour votre personnage joueur. Les rôles disponibles sont voleur, mage, guerrier et prêtre.
   - Chaque rôle a des attributs différents (santé et dégâts) qui seront sélectionnés aléatoirement à partir d'une base de données.


2. **Choix du Nombre de Tours**
   - Après avoir créé votre personnage, on vous demandera de saisir le nombre de tours que vous souhaitez jouer. Le nombre minimum de tours est de 6.


3. **Exploration des Lieux**
   - Pendant chaque tour, vous pouvez choisir l'une des quatre directions : Nord, Est, Sud ou Ouest.
   - Des événements aléatoires se produiront dans chaque lieu, notamment la découverte de trésors, la rencontre d'ennemis ou le déclenchement d'autres événements spéciaux.


4. **Combat**
   - Si vous rencontrez un ennemi, vous vous engagez dans un combat au tour par tour avec lui. Chaque personnage attaquera à tour de rôle, et le combat se poursuivra jusqu'à ce que la santé d'un personnage atteigne zéro.


5. **Gagner et Perdre**
   - Le jeu se poursuivra pendant le nombre de tours spécifié. Si vous survivez à tous les tours, vous gagnez la partie.
   - Si la santé de votre personnage tombe à zéro ou en dessous, vous perdez la partie et le jeu se terminera.

 
## Remerciements

 

Ce jeu a été créé en utilisant Python et intègre des concepts de programmation orientée objet, d'événements aléatoires et d'interactions basées sur du texte. 
Le projet utilise des données de différentes classes telles que `Data`, `Character`, `Player` et `Narrator` pour donner vie à l'histoire.

 

Le jeu est conçu pour être une aventure textuelle amusante et interactive où les choix du joueur influencent le déroulement de l'histoire. 
Profitez de l'exploration des différents lieux, des défis rencontrés et des décisions qui façonnent le destin de votre personnage !

 

**Note :** Ce README est un guide général pour comprendre le jeu. Vous pouvez trouver des informations supplémentaires et de la documentation dans le code source lui-même.

 

**Amusez-vous à jouer au jeu !**
