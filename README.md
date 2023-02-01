# Nour-Eddine-Projet-Tp
 
  <h1 align="center">PROJET API CI/CD  ESIREM 2023</h1>
  
## Sujet : 
  Sujet guidé
  
 ## Réalisé par : 
  ZAIDI Nour-Eddine
  
  
  
# L'objectif consiste à contrôler la gestion CRUD d'un système de transaction.

   ![Badge1](https://i0.wp.com/datascientest.com/wp-content/uploads/2021/03/illu_devops_blog-119.png?resize=1024%2C562&ssl=1.png)



## Langage utilisé :
  Python 
  
## Fonctionnalités :

-Initialisation de l'application Flask

-Route pour afficher toutes les personnes et les transactions

-Route pour affichier les transactions sauvegargdées dans un fichier csv entre 2 personnes.

## Utilisation :

-Installation de flask avec :
    pip install flask
   
- Lancer l'application localement sur Linux :
   export FLASK_APP=main.py
   export FLASK_APP=development
   flask run


## Routes 

   Pour enregistrer une transaction, nous avons besoin :
   De l'id de la personne donnant de l'argent
   De l'id de la personne recevant de l'argent
   Du moment où nous allons enregistrer la transaction
   La somme d'argent que P1 va donner à P2
   Tout ceci est mis dans une commande curl

   curl -X POST -d "personne1=1&personne2=2&temps=10&somme=50" http://localhost:5000/transaction
   
   
   
## Vous trouverez ci-dessus les différentes actions utilisées dans ce projet : 

App build :
![Generic badge](https://github.com/Nordine34Projet-Tp/actions/workflows/buildstage.yml/badge.svg)

Build docker image :
![Generic badge](https://github.com/Nordine34/Projet-Tp/actions/workflows/newimage.yml/badge.svg)

Build and push tag :
![Generic badge](https://github.com/Nordine34/Projet-Tp/actions/workflows/push.yml/badge.svg)
