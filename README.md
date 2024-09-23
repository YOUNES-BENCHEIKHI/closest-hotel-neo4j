Fonctionnalités
Stockage des données d'hôtels : Les hôtels sont modélisés sous forme de nœuds dans un graphe, avec leurs coordonnées géographiques (latitude et longitude) comme propriétés.
Localisation de l'utilisateur : La localisation actuelle de l'utilisateur est récupérée en utilisant une entrée manuelle ou une API de géolocalisation.
Calcul de la distance : Le projet utilise la fonction de calcul de distance géographique (Haversine) pour déterminer l'hôtel le plus proche en fonction de la localisation de l'utilisateur.
Requêtes Cypher : Le moteur de requêtes Cypher permet de rechercher et de classer les hôtels en fonction de la distance par rapport à l'utilisateur.
Technologies utilisées
Neo4j : Pour la gestion des données des hôtels et des relations spatiales.
Cypher : Langage de requête pour Neo4j.
API de géolocalisation (optionnel) : Pour récupérer la position actuelle de l'utilisateur.
