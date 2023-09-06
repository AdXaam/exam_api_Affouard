# exam_api_Affouard

1) Donner 5 verbes HTTP et expliquer leur utilité (2 points)

GET est utilé pour récupérer les données à partir d'une source distante comme une base de données.
POST permet de soumettre des données au serveur afin de créer une ressource. (Les films dans notre exercice)
PUT permet de mettre à jour une ressource dans sa totalité.
PATCH permet d'appliquer des modifications partielles à une ressource.
DELETE permet de supprimer une ressource.

2) Donnez les composants d’une requête HTTP (2 points)

La méthode : on retrouve courrament les verbes HTTP cités au dessus dans les méthodes.
L'URL : cela va indiquer au serveur l'emplacement de la ressource. On retrouve ici le protocole (HTTP ou HTTPS), le nom de domaine, le chemein d'accès et potentiellement des paramètres
Les Headers : cela correspond aux métadonnées de la requete. 
Le Body : contient les données envoyées au serveur. En GET, il n'y a pas de Body.

3) Donnez les composants d’une réponse HTTP (2 points)

Le code d'état HTTP : il s'agit d'un nombre a trois chiffres qui va indiquer le résultat de la requête. Il en existe plusieurs tels que "404 NotFound" et d'autres.
Les Headers : il s'agit des métadonnées de la réponse. 
Le Body : contient les données renvoyées par le serveur. 
