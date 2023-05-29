# nombre_mystère

## Présentation

Dans ce projet, vous allez créer un jeu interactif dans lequel l'ordinateur
choisira un nombre aléatoire et vous devrez essayer de deviner ce nombre en
utilisant des indices. Vous aurez 10 tentatives pour trouver le nombre mystère.

## Prérequis

- Installation de Python : Assurez-vous d'avoir Python installé sur votre
  ordinateur. Vous pouvez télécharger la dernière version stable de Python
  depuis le site officiel (https://www.python.org). Si vous utilisez Linux, il
  y a de grandes chances que Python soit déjà installé. Sinon, installez-le
  avec votre gestionnaire de paquets.
- Éditeur de code : Vous aurez besoin d'un éditeur de code pour écrire votre
  programme en Python. Il existe de nombreux éditeurs disponibles tels que
  Visual Studio Code, PyCharm, Sublime Text, Neovim etc. Choisissez celui avec
  lequel vous êtes à l'aise. Si nous ne savez pas lequel choisir, choisissez
  Visual Studio Code.
- Connaissance de la syntaxe de base de Python : Familiarisez-vous avec la
  syntaxe de base de Python, y compris la déclaration de variables, les boucles
  (for et while), les structures conditionnelles (if/else) et les fonctions.
- Bibliothèque random : La bibliothèque "random" de Python sera utilisée pour
  générer des nombres aléatoires. Assurez-vous de comprendre comment l'importer
  et utiliser ses fonctions.

## Compétences

- Compréhension des concepts de base de la programmation, tels que les
  variables, les conditions et les boucles.
- Capacité à utiliser des instructions d'entrée/sortie pour interagir avec
  l'utilisateur.
- Connaissance des opérations de comparaison pour évaluer les conditions.
- Aptitude à générer des nombres aléatoires dans un intervalle donné.
- Capacité à structurer et organiser le code en utilisant des fonctions ou des
  classes (facultatif, mais recommandé pour une meilleure lisibilité du code).

## Consigne
 
1. L'ordinateur doit choisir un nombre aléatoire entre 1 et 100, et le joueur
doit essayer de le deviner.
2. Le jeu doit afficher un message d'accueil et demander au joueur d'entrer un
nombre.
3. Si le nombre entré par le joueur est inférieur au nombre choisi par
l'ordinateur, le jeu doit afficher un message indiquant que le nombre est trop
bas, et demander au joueur d'entrer un nouveau nombre.
4. Si le nombre entré par le joueur est supérieur au nombre choisi par
l'ordinateur, le jeu doit afficher un message indiquant que le nombre est trop
élevé, et demander au joueur d'entrer un nouveau nombre.
5. Si le joueur devine correctement le nombre, le jeu doit afficher un message
de félicitations et indiquer le nombre total d'essais effectués.
6. Si le joueur n'a pas deviné le nombre après 10 tentatives, le jeu doit
afficher un message indiquant qu'il a épuisé toutes ses chances et révéler le
nombre mystère.
7. Une fois que le joueur a deviné correctement le nombre ou épuisé toutes ses
chances, le jeu doit lui demander s'il souhaite jouer à nouveau. Si le joueur
répond par l'affirmative, un nouveau nombre doit être choisi par l'ordinateur
et le jeu continue avec 10 nouvelles tentatives. Sinon, le jeu doit afficher un
message de fin et se terminer.
