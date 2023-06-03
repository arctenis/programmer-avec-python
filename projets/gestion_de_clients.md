# Gestion d'un portefeuille de clients

## Présentation

Dans ce projet, vous allez construire une application simple de gestion de
clients pour un travailleur indépendant. L'application aidera l'utilisateur à
suivre ses clients et les détails de chaque projet. 

## Prérequis

Nous partons du principe que vous avez déjà réalisé vos premiers projets en
Python.

- Connaissance de base en Python
- Compréhension des concepts de base de la programmation orientée objet
  (classes, objets, méthodes, héritage)

## Compétences

- Création et utilisation de classes et d'objets en Python
- Compréhension et application des principes de l'héritage et du polymorphisme
- Connaissance pratique de la construction d'une application simple avec une
  architecture orientée objet

## Consignes

1. **Création de classes et d'objets** : Créez une classe "Client" avec des
   attributs tels que "nom", "adresse_email" et "budget_projet". Ensuite, créez
   plusieurs instances de cette classe et imprimez les attributs de chaque
   instance.

2. **Méthodes d'instance** : Ajoutez une méthode "envoyer_facture" à la classe
   "Client". Cette méthode doit imprimer un message indiquant qu'une facture a
   été envoyée au client, avec le montant correspondant. Ensuite, appelez cette
   méthode sur chaque instance de la classe.

3. **Constructeur et destructeur** : Modifiez la classe "Client" pour ajouter
   une méthode `__init__` qui initialise les attributs de la classe. Ajoutez
   également une méthode `__del__` qui imprime un message lorsqu'une instance
   est supprimée.

4. **Héritage** : Créez une classe "Client régulier" qui hérite de la classe
   "Client". Ajoutez un attribut "réductions" et une méthode
   "appliquer_réduction" qui ajuste le budget du projet en fonction des
   réductions disponibles.

5. **Polymorphisme** : Créez plusieurs classes pour différents types de clients
   (par exemple, "Client entreprise", "Client individuel", "Client à long
   terme"). Chaque type de client peut avoir des attributs supplémentaires le
   cas échéant. De plus, chaque type de client doit avoir une méthode
   "envoyer_facture" légèrement différente qui prend en compte des
   considérations spécifiques (par exemple, des taxes différentes, des
   conditions de paiement différentes, etc.).

## Suite

Voici quelques pistes pour aller plus loin avec ce projet :

1. **Intégration avec une base de données** : Intégrez votre application à une
   base de données en utilisant TinyDB pour stocker des informations sur les
   clients et les factures. Cela implique l'apprentissage des opérations CRUD
   (Create, Read, Update, Delete) et l'application de ces opérations à vos
   objets.

2. **Création d'une interface utilisateur** : Ajoutez une interface utilisateur
   simple à votre application. Cela peut être aussi simple qu'un menu dans la
   console qui permet à l'utilisateur de choisir parmi différentes options (par
   exemple, ajouter un nouveau client, modifier un client existant, supprimer
   un client, etc.).

3. **Génération de factures en PDF** : Intégrez une bibliothèque Python comme
   ReportLab ou pdfkit pour générer des factures en PDF. Chaque facture doit
   inclure toutes les informations pertinentes sur le client et le projet.

4. **Ajout de fonctionnalités supplémentaires** : Envisagez d'ajouter des
   fonctionnalités supplémentaires à votre application, comme le suivi du temps
   de travail sur chaque projet, la gestion des paiements, la possibilité
   d'envoyer des factures par email, etc.
