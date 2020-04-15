# Projet 4 -  ANALYSEZ LES BESOINS DE VOTRE CLIENT POUR SON GROUPE DE PIZZERIAS  
 
--
# Table_des_matières  

[Contexte_fictif](#Contexte_fictif)  
[Objet_du_document](#Objet_du_document)  
[Contexte](#Contexte)  
[Objectifs](#Objectifs)  
[Les_spécialisations_fonctionnelles](#Les_spécialisations_fonctionnelles)  
[Les_différents_acteurs](#Les_différents_acteurs)  
[Les_domaines_fonctionnels](#Les_domaines_fonctionnels)  
[Les_cas_d'utilisation_généraux](#Les_cas_d'utilisation_généraux)  
[Les_cas_d'utilisation_détaillés](#Les_cas_d'utilisation_détaillés)  
[Le_cycle_de_vie_d'une_commande](#Le_cycle_de_vie_d'une_commande)  
[La_solution_fonctionnelle_et_technique](#La_solution_fonctionnelle_et_technique)  
[Version](#Version)  
 
--
# Contexte_fictif  
    Vous travaillez chez « IT Consulting & Development ».  
    C’est une petite entreprise d’une vingtaine d’employés  
    capable de mener des projets informatiques de développement logiciel/mobile/web.  
    Vous êtes un développeur d'application junior et, récemment,  
    vous vous êtes également outillé pour mener l’analyse des besoins client  
    lors des lancements de projets  

Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# Objet_du_document  
Le présent document constitue le dossier de conception fonctionnelle de l'application OC PIZZA  
Il reprend l’ensemble des documents décrivant le comportement des organes,  
fonctionnalités et sous-fonctions de la solution cible,  
en respectant les besoins exprimés par notre client, OC Pizza.  

Retour à la [Table_des_matières](#Table_des_matières)  
  
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
[Source : toutelafranchise](https://www.toute-la-franchise.com)  

L'entreprise

    OC Pizza est un jeune groupe de pizzeria en plein essor.  
    Crée par Franck et Lola, le groupe est spécialisé dans les pizzas livrées ou à emporter.  
    Il compte déjà 5 points de vente et prévoit d’en ouvrir au moins 3 de plus d’ici 6 mois.  
    Le système informatique actuel ne correspond plus aux besoins du groupe,  
    car il ne permet pas une gestion centralisée de toutes les pizzerias.  
    De plus, il est très difficile pour les responsables de suivre ce qui se passe dans les points de ventes.  
    Enfin, les livreurs ne peuvent pas indiquer « en live » que la livraison est effectuée.  

Retour à la [Table_des_matières](#Table_des_matières)  
  
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
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# Les_spécialisations_fonctionnelles
Dans cette partie, les éléments suivants seront présentés et détaillés :  
    
    -	L’analyse des besoins du client
    -	La description générale de la solution
    -	Le domaine fonctionnel
    -	Le flux fonctionnel
    -	Les cas d’utilisations
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les_différents_acteurs  
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
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les_domaines_fonctionnels  
L'application se découpe en deux domaines fonctionnels :  
    
    - Le Front Office  
    - Le Back Office  
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les cas_d'utilisation_généraux  
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
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les cas_d'utilisation_détaillés  
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
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Le cycle_de_vie_d'une_commande  
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
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# La solution_fonctionnelle_et_technique

    Rédaction en cours ...
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# Version
    1.2
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--