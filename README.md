# L'eau sur le campus de l'UNIL
Projet de visualisation de données

## Description
Notre projet propose une visualisation interactive des différentes possibilités d’obtenir de l’eau sur le campus de l’Université de Lausanne. À l’heure des prises de conscience environnementale et des innombrables débats sur les changements climatiques, les thèmes de l’eau, de sa disponibilité et de sa gestion sont centraux. Ce projet propose de mettre en avant un thème universel grâce à un exemple local de la vie quotidienne à l’UNIL, à savoir la multiplicité des sources d'eau en bouteille (principalement en plastique) malgré une offre en eau potable au robinet très étendue.

## Données
Les données ont été récoltées par nos soins, en relevant, dans chaque bâtiment, les différentes options permettant d'obtenir de l'eau. Elles comprennent les éléments suivants:
 - Lieu (bâtiment)
 - Point de vente (cafétéria, machine, ...)
 - Marque
 - Variante
 - Prix
 - Volume
 - Plate ou gazeuse

Par la suite, des recherches ont été menées pour rajouter le groupe industriel propriétaire de chacune des marques, ainsi que la localisation de la source dont provient l'eau mise en bouteille (lieu, pays, latitude, longitude).
Une fois complétées, les données ont été saisies sous la forme d'un fichier JSON.

## Interface
La page est séparée en deux parties.
En haut, un graphique permet de visualiser le nombre de sources (bouteilles et robinets) par bâtiment, ou par groupe industriel.
La deuxième partie de la page donne des informations plus précises sur les eaux, leurs caractéristiques (naturelle ou pétillante), leur prix, le lieu où elles sont disponibles ainsi que leur volume. Il est possible de cliquer sur chaque marque afin d’afficher les informations détaillées sur un produit. La couleur des bouteilles correspond à celle des bâtiments sur le graphique.

## Développements futurs
- La granularité de la représentation des sources disponibles en histogramme gagnerait à être augmentée, afin que les différentes bouteilles disponibles soient représentées en barres superposées.
- Les coordonnées géographique des sources ayant été inclues dans les données JSON, il serait possible d'ajouter une visualisation du trajet effectué par l'eau contenue dans les bouteilles, de leur source à leur point de vente.

## Crédits
Ce projet a été réalisé par Lucile Berset et Jean Ceppi dans le cadre du cours _Visualisation de données_, dispensé par Isaac Pante à l'Université de Lausanne, entre 2018 et 2019.
