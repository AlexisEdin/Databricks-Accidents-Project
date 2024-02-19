# Databricks-Accidents-Project
Projet exam AZURE


Présentation du projet : 

L'objectif du projet est de déterminer via le meilleur modèle prédictif le type d'accident via les différentes variables détaillant l'accident de la route. 
La variable prédictive va de 1 à 4, echelle correspondant à la gravité de l'accident. 

Sources de données : 

4 fichiers CSV : Veh / Vict / Lieux / Carac. Ils proviennent du tuto d'Iliyes : https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/

Dans le répository : 

Un fichier ReadMe, deux notebooks, les 4 fichiers CSV et des liens utiles. 

Modèle retenu : 

Le modèle retenu est celui du randomforest car il obtient les meilleures metriques (accurancy et F1-score) : accurancy : 0.64 / F1 score : 0.441

Le lien Endpoint du Modèle : 

https://adb-2496514911367531.11.azuredatabricks.net/serving-endpoints/3emetest/invocations

token : 

dapi1fbd878c68b49281d8089748b69c8ba7-2
