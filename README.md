#Projet 4 -  ANALYSEZ LES BESOINS DE VOTRE CLIENT POUR SON GROUPE DE PIZZERIAS


## Table des matières  

[Objet du document](##Objet du document)  
[Contexte](##Contexte)  
[Objectifs](##Objectifs)  
[Les spécialisations fonctionnelles](##Les spécialisations fonctionnelles)  
[Les acteurs](###Les différents acteurs)  
[Les domaines fonctionnels](###Les domaines fonctionnels)  
[Les cas d'utilisation généraux](###Les cas d'utilisation généraux)  
[Les cas d'utilisation détaillés](###Les cas d'utilisation détaillés)  
[Le cycle de vie d'une commande](###Le cycle de vie d'une commande)  
[La solution fonctionnelle et technique](##La solution fonctionnelle et technique)  
[Version](#Version)  
 
--
## Objet du document  
 
--
## Contexte  
Le secteur

    Le marché de la pizza en France est dominé par les restaurants italiens et autres pizzerias.  
    Ces établissements pèsent à eux seuls pour 48% de parts de marché en nombre de pizzas.  
    Viennent ensuite la grande distribution avec 25% de parts de marché,  
    la restauration collective avec 15% et les camions, livreurs, et restauration automatique avec 12%.  
    L'innovation en matière de pizza est aussi à aller chercher du côté des formats proposés  
    (ventes à la part, pizzas à partager, mini-pizzas, etc.),  
    et de la façon de présenter l'offre avec notamment de plus en plus de recettes personnalisables.  
    L'ajout de services comme la livraison à domicile ou au bureau n'est pas en reste.  
[Source : toutelafranchise](toutelafranchise.com)  

L'entreprise

    OC Pizza est un jeune groupe de pizzeria en plein essor.  
    Crée par Franck et Lola, le groupe est spécialisé dans les pizzas livrées ou à emporter.  
    Il compte déjà 5 points de vente et prévoit d’en ouvrir au moins 3 de plus d’ici 6 mois.  
    Le système informatique actuel ne correspond plus aux besoins du groupe,  
    car il ne permet pas une gestion centralisée de toutes les pizzerias.  
    De plus, il est très difficile pour les responsables de suivre ce qui se passe dans les points de ventes.  
    Enfin, les livreurs ne peuvent pas indiquer « en live » que la livraison est effectuée.  

 
--
## Objectifs  
L’objectif du projet est de proposer à OC Pizza un outil informatique réalisant les fonctions suivantes : 

    - Mettre en avant et rendre accessible l’ensemble des points de ventes via une boutique en ligne. 
    - Concentrer la gestion et la supervision de tous les points de ventes.
    - Permettre l’indication et la consultation, en temps réel, des évènements de chaque point de vente.

Cette solution devra être livrable pour l’ouverture des trois nouvelles pizzerias, dans les six mois à venir.

    La solution cible est un site permettant d’offrir une boutique en ligne, pour la prise de commande,
    une gestionnaire centralisée, pour le suivi des commandes en temps réel
    et la supervision des données relative à chaque point de vente.  
 
--
## Les spécialisations fonctionnelles  
 
--
### Les différents acteurs  
Le consommateur est une estimation générale. Il peut être un des utilisateurs suivants :  

    - le visiteur
    - le caissier
    - le futur client
    - le client  
Concernant le personnel de l'entreprise, trois acteurs ont été identifiés :

    - Le responsable
    - Le pizzaiolo
    - Le livreur.

Une entité supplémentaire est identifée, un système bancaire, permettant l'exécution de transactions bancaires  
pour le réglement des commandes en ligne.

    - Le système bancaire
 
--
### Les domaines fonctionnels  
L'application se découpe en deux domaines fonctionnels :  
    
    - Le Front Office  
    - Le Back Office  
 
--
### Les cas d'utilisation généraux  
Les fonctionnalités du domaine fonctionnel - Font Office :      

    - La consultayion du catalogue
    - L'enregistrement d'une commande
    - La modification d'une commande
    - L'annulation d'une commande

Les fonctionnalités du domaine fonctionnel - Back Office :  

    - La gestion des matières premières
    - L'inspection des matières premières
    - L'inspection des commandes
    - La gestion des commandes

 
--
### Les cas d'utilisation détaillés  
Ci-dessous, la liste des fonctionnalités principales :  

    - Consulter catalogue
    - Enregistrer une commande
    - Modifier une commande
    - Annuler une commande
    - Créer un compte
    - Consulter l'historique
    - Obtenir une promotion
    - Indiquer la prise en charge de commande
    - Indiquer la préparation de la commande
    - Indiquer commande prête
    - Consulter les pizzas réalisables
    - Consulter les commandes à réaliser
    - Indiquer la prise en charge de la commande
    - Indiquer la livraison de la commande
    - Suivre le statut de la commande
    - Modifier le stock d'ingrédients
    - Modifier les recettes de pizzas

Ci-dessous, la liste des fonctionnalités internes : 

    - Fournir informations personnelles
    - Constituer panier
    - Obtenir récapitulatif
    - Payer une commande
    - Sélectionner une pizza disponible
    - Consulter une commande
    - Payer en ligne
    - Payer à la livraison
    - S'authentifier
    - Consulter les recettes de pizzas
    - Consulter le stock d'ingrédients
 
--


### Le cycle de vie d'une commande  
Ci-dessous, le fil d'exécution du système vis-à-vis de la gestion d'une commande. Il reprend dans ce fil d'éxuction,  
le rôle des fonctionnalités détaillées qui sont identifiées dans les deux domaines fonctionnels :

    1. Consulter catalogue
    2. Constituer panier
    3. Fournir informations personnelles
    4. Payer une commande
    5. Obtenir récapitulatif
    6. Consulter les commandes à réaliser
    7. Indiquer la prise en charge de la commande
    8. Indiquer la préparation de la commande
    9. Indiquer commande prête
    10. Indiquer la prise en charge de la commande
    11. Indiquer la livraison de la commande

 
--
## La solution fonctionnelle et technique  

    Rédaction en cours ...
 
--
# Version
    1.0
 
--