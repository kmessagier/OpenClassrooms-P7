# OpenClassrooms-P7
Projet 7 - 1/ Implémentez un modèle de scoring

1/3
Implémentez un modèle de scoring
openclassrooms.com/fr/projects/implementez-un-modele-de-scoring/assignment
120 heuresMis à jour le jeudi 1 juillet 2021
Vous êtes Data Scientist au sein d'une société financière, nommée "Prêt à
dépenser",  qui propose des crédits à la consommation pour des personnes ayant peu ou
pas du tout d'historique de prêt.
 
 
L’entreprise souhaite développer un
modèle de scoring de la
probabilité de défaut de paiement
du client pour étayer la décision
d'accorder ou non un prêt à un client
potentiel en s’appuyant sur des sources
de données variées (données
comportementales, données provenant
d'autres institutions financières, etc.).
De plus, les chargés de relation client
ont fait remonter le fait que les clients
sont de plus en plus demandeurs de
transparence vis-à-vis des décisions
d’octroi de crédit. Cette demande de
transparence des clients va tout à fait dans le sens des valeurs que l’entreprise veut
incarner.
Elle décide donc de développer un dashboard interactif pour que les chargés de
relation client puissent à la fois expliquer de façon la plus transparente possible les
décisions d’octroi de crédit, mais également permettre à leurs clients de disposer de leurs
informations personnelles et de les explorer facilement. 
Les données
Voici les données dont vous aurez besoin pour réaliser le dashboard. Pour plus de
simplicité, vous pouvez les télécharger à cette adresse.
Vous aurez sûrement besoin de joindre les différentes tables entre elles.
Votre mission


1. Construire un modèle de scoring qui donnera une prédiction sur la probabilité de
faillite d'un client de façon automatique.


2. Construire un dashboard interactif à destination des gestionnaires de la relation
client permettant d'interpréter les prédictions faites par le modèle et d’améliorer la
connaissance client des chargés de relation client.


2/3
Michaël, votre manager, vous incite à sélectionner un kernel Kaggle pour vous faciliter la
préparation des données nécessaires à l’élaboration du modèle de scoring. Vous
analyserez ce kernel et l’adapterez pour vous assurer qu’il répond aux besoins de votre
mission.
Vous pourrez ainsi vous focaliser sur l’élaboration du modèle, son optimisation et sa
compréhension.
Spécifications du dashboard
Michaël vous a fourni un cahier des charges pour le dashboard interactif. Celui-ci
devra a minima contenir les fonctionnalités suivantes :
Permettre de visualiser le score et l’interprétation de ce score pour chaque client de
façon intelligible pour une personne non experte en data science.
Permettre de visualiser des informations descriptives relatives à un client (via un
système de filtre).
Permettre de comparer les informations descriptives relatives à un client à
l’ensemble des clients ou à un groupe de clients similaires
