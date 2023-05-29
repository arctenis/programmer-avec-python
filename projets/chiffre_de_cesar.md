# Le chiffre de César

## Présentation

Le Chiffre de César tire son nom de Jules César, qui l'aurait utilisé pour
communiquer de manière sécurisée avec ses généraux lors de ses campagnes
militaires. Il s'agit d'une méthode de chiffrement par décalage, dans laquelle
chaque lettre du message clair est remplacée par une lettre décalée d'un
certain nombre de positions dans l'alphabet. Par exemple, avec une clé de
décalage de 3, 'A' devient 'D', 'B' devient 'E', et ainsi de suite.

Dans ce projet, vous allez créer un programme qui demande à l'utilisateur une
clé de chiffrement, un message à chiffrer et qui produit le message chiffré en
utilisant cette méthode.


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

## Compétences

- Compréhension des concepts de base de la programmation, tels que les
  variables, les conditions et les boucles.
- Capacité à manipuler les chaînes de caractères (string) en Python.
- Connaissance des opérations mathématiques de base, notamment les opérations
  modulo (%).
- Aptitude à gérer les entrées/sorties utilisateur pour obtenir les
  informations nécessaires.
- Capacité à organiser et structurer le code en utilisant des fonctions ou des
  classes (facultatif, mais recommandé pour une meilleure lisibilité du code).

## Consignes

- Demandez à l'utilisateur de saisir une clé de chiffrement, qui sera un nombre
  entier.
- Demandez à l'utilisateur de saisir le message à chiffrer.
- Chiffrez le message en utilisant le chiffre de César : décalez chaque lettre
  du message initial vers la droite de la valeur de la clé. Par exemple, si la
  clé est 3, 'A' devient 'D', 'B' devient 'E', et ainsi de suite.
- Vous pouvez ignorer les caractères spéciaux et les espaces dans le
  chiffrement.
- Affichez le message chiffré à l'utilisateur.

Optionnel :
- Assurez-vous de prendre en compte les majuscules et les minuscules dans le
  chiffrement, en conservant la casse d'origine du message.
- Le programme doit être capable de gérer des clés négatives, qui décaleront
  les lettres vers la gauche.
- Le programme peut prendre en argument un fichier texte contenant le message à
  chiffrer, et écrire le message chiffré dans un autre fichier texte.

## Suite

### Attaque par force brute

Le chiffre de César est un chiffrement très faible, car il est très facile à 
casser. En effet, il n'y a que 26 clés possibles, ce qui signifie qu'il est 
possible de tester toutes les clés possibles pour trouver la bonne clé. C'est 
ce qu'on appelle une attaque par force brute.

Dans ce projet, vous allez créer un programme qui permet de casser un message
chiffré par le chiffre de César en utilisant une attaque par force brute. 
L'utilisateur devra fournir le message chiffré, et le programme devra tester 
toutes les clés possibles pour trouver la bonne clé. 

Le programme affichera toutes les solutions une par une.
