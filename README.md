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
[Les_fonctionnalités_générales](#Les_fonctionnalités_générales)  
[Les_fonctionnalités_détaillées](#Les_fonctionnalités_détaillées)  
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
[Source : toutelafranchise](https://www.toute-la-franchise.com/vie-de-la-franchise-A31771-ouvrir-pizzeria-2019.html)  

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

Deux entités supplémentaires sont identifées. D'une part, un système bancaire,  
permettant l'exécution de transactions bancaires  
pour le réglement des commandes en ligne. D'autre part, un système d’authentification externe  
lié à un réseau social.  

    - Le système bancaire
    - Le système d'authentifiaction externe
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les_domaines_fonctionnels  
L'application se découpe en deux domaines fonctionnels :  
    
    - Le Front Office  
    - Le Back Office  
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Les_fonctionnalités_générales  
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
### Les_fonctionnalités_détaillées  
Ci-dessous, la liste des fonctionnalités principales :  

    - Consulter catalogue
    - Enregistrer une commande
    - Modifier une commande
    - Annuler une commande
    - Créer un compte
    - Consulter l'historique
    - Obtenir une promotion
    - Modifier statut commande
    - Consulter les pizzas réalisables
    - Consulter les commandes à réaliser
    - Suivre le statut de la commande
    - Modifier le stock d'ingrédients
    - Modifier les recettes de pizzas
    - Gestion utilisateurs

Ci-dessous, la liste des fonctionnalités internes : 

    - Fournir informations personnelles
    - Constituer panier
    - Obtenir récapitulatif
    - Payer une commande
    - Consulter une commande
    - Payer en ligne
    - Payer à la livraison
    - S'authentifier
    - Authentification interne
    - Authentification externe
    - Consulter les recettes de pizzas
    - Consulter le stock d'ingrédients
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
### Le_cycle_de_vie_d'une_commande  
Ci-dessous, le fil d'exécution du système vis-à-vis de la gestion d'une commande. Il reprend dans ce fil d'éxuction,  
le rôle des fonctionnalités détaillées qui sont identifiées dans les deux domaines fonctionnels :

    1. Consulter catalogue
    2. Constituer panier
    3. Fournir informations personnelles
    4. Payer une commande
    5. Obtenir récapitulatif
    6. Consulter les commandes à réaliser
    7. Modifier statut commande
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# La_solution_fonctionnelle_et_technique

    Rédaction en cours ...
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# Sources  
L'ensemble des choix technologiques de la solution technique,  
a été basée sur des recherches et des études de marchés réalisés entre 2017 et 2019.
Ces sources sont fiables et permettent un choix mesuré, actuel et compétitif,  
en termes de technologie. Ci-dessous, quelques sites et articles :  
- lafabriquedunet.fr : [Les hébergements WEB](https://www.lafabriquedunet.fr/blog/comparatif-hebergement-web/#h2_1)   
- hostinger.fr : [Hostinger / Les meilleurs CMS](https://www.hostinger.fr/tutoriels/meilleurs-cms)
- lws.fr : [LWS / Les meilleurs CMS](https://blog.lws-hosting.com/creation-de-sites-web/top-5-meilleurs-systemes-de-gestion-de-contenus-2017)
- ovh.com : [OVH / Les meilleurs CMS](https://www.ovh.com/fr/hebergement-web/site/comparatif-cms/)
- lafabriquedunet.fr : [Les solutions paiement en ligne](https://www.lafabriquedunet.fr/blog/comparatif-meilleures-solutions-paiement-en-ligne/)  
- codeur.com : [Les solutions paiement en ligne](https://www.codeur.com/blog/solutions-paiement-en-ligne-ecommerce/)  
- stripe.com : [API Stripe](https://stripe.com/docs/api)
- hipay.com : [API Hipay](https://developer.hipay.com/api-explorer/api-online-payments)  
- paypal.com : [API Paypal](https://developer.paypal.com/docs/api/overview/)  
- google.com : [API Google Sign-in](https://developers.google.com/identity/sign-in/web/sign-in)  
- facebook.com : [API Facebook login](https://developers.facebook.com/docs/facebook-login/web)
Retour à la [Table_des_matières](#Table_des_matières)  
 
--
# Version
    1.4
 
Retour à la [Table_des_matières](#Table_des_matières)  
 
--