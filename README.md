# <center>**Truc qui restent à faire pour le projet de MLG**<center>


* Fini et validé :green_square:
* Fini mais à valider :violet_square:
* Point d'attention / à compléter :yellow_square:
* En cours :orange_square:
* Reste à faire :red_square:



# Contexte de l’étude et objectifs :green_square:
*Description : Intro du doc de la prof.*  
# Organisation des répertoires  :violet_square:
*Description : Liste comment doivent être mis les documents de base (notebook et images) dans le répertoir pour le bon fonctionnement du code.*  
# Librairies  :yellow_square:
*Description : Liste des modules python utilisés classés par ordre alphabétique.*  
# Préparation des images :yellow_square: 
*Description : Stacking et découpage des images pour leur utilisation ultérieure.*  
**Commentaire :** Peut-être revoir ce qu'on garde ou non ? Notamment les images de mayotte entières et les bandes (Est-ce qu'on justifie celles qu'on garde ici ou plus tard quand on entraînera des modèles)  


# **Objectif 1 : exploration des images satellites**  :yellow_square:

## Caractéristiques principales des images  :yellow_square:
*Description : Présenter les principales caractéristiques des images : dates d'acquisition, résolution spatiale, bandes spectrales et dimensions.*  
**Commentaire :** Est-ce qu'on ajoute quelques descriptifs en plus ? Dans le tableau ou en texte en plus ?  
## Visualisation des images  :violet_square:
*Description : Produire des compositions colorées permettant de visualiser l'occupation du sol aux 2 dates.*
## Zonage autour des pièges  :yellow_square:
*Description : Identifier les zones d'intérêt à proximité des pièges à moustiques.*
**Commentaires :** Je suis partie sur un découpage des zones autour des pièges et on affiche un exemple de zone. Est-ce que tu l'interprètes pareil cette question ?  


# **Objectif 2 : Calcul et comparaison des indicateurs spectraux**  :red_square:

## Calcul des indices spectraux :red_square:
*Description : Choix puis calcul des indices spectraux*  
## Visualisation des indices spectraux :red_square:
*Description : Produire des cartes des indices sélectionnés aux deux dates.*  
## Variation des indices spectraux entre 2019 et 2024 :red_square:
*Description : Calculer les différences entre les deux dates (par exemple, ΔNDVI) et Interpréter les changements en tenant compte des limites de ces indicateurs.*  


# **Objectif 3 : Classification de l'occupation du sol**  :red_square:

## Choix des classes et de la méthode de classification :red_square:
*Description : Définir une nomenclature de classes pertinente : végétation, bâti, sols nus, eau, etc et Présenter et justifier la méthode de classification retenue.*  
## Visualisation des résultats de la classification :red_square:
*Description : Produire une carte d’occupation du sol supervisée pour 2019 et 2024 avec une nomenclature identique.*  
## Évaluation de la qualité de la classification :red_square:
*Description : Évaluer la qualité des classifications, en utilisant des données de validation lorsque celles-ci sont disponibles, proposez quelques scores et Discuter les principales sources d'erreur et les limites de votre méthode.*  


# **Objectif 4 : Détection et quantification des changements**  :red_square:

## Calcul des variations d'occupation du sol entre 2019 et 2024 à partir des classifications :red_square:
*Description : A partir des cartes d'occupation du sol quantifier et cartographier les changements d’occupation du sol entre les deux dates et Identifier les principales transitions : végétation vers bâti, végétation vers sol nu, etc et Quantifier les surfaces concernées par ces changements.*  
## Comparaison avec les variations d'indices spectraux :red_square:
*Description : Comparer les résultats issus des classifications avec ceux obtenus à partir des différences d'indices spectraux et Discuter la cohérence des changements détectés et les incertitudes associées.*  


# **Objectif 5 : Analyse environnementale à proximité des pièges à moustiques**  :red_square:

## Caractérisation de l'occupation du sol autour des pièges :red_square:
*Description : Caractériser l'occupation du sol autour des pièges aux deux dates.*  
## Quantification des variations d'occupation du sol autour des pièges entre 2019 et 2024 :red_square:
*Description : Quantifier les changements de végétation, de surfaces bâties et éventuellement de surfaces en eau autour des pièges et Comparer les valeurs des indicateurs spectraux entre les deux dates et Identifier les transformations environnementales susceptibles de modifier les habitats favorables aux moustiques.*  
## Les limites de l'interprétation écologique :red_square:
*Description : Discuter les limites de l'interprétation écologique : les changements d'occupation du sol ne permettent pas, à eux seuls, de conclure à une modification de l'abondance des moustiques.*  


# **Objectif 6 : Risque et probabilité de présence (optionnel)**  :red_square:
