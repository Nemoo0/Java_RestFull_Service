# Utilisation
Pour pouvoir utiliser ce service il vous faut d'abord importer les deux projets dans votre IDE favori.

## Serveur
Ensuite rentrez dans le dossier du **serveur** : 

`cd /home/user/rest-service-server`

Effectuer la commande :

`./mvnw clean package`

Pour construire un fichier **JAR** éxécutable.

Démarrer le avec la commande :

`java -jar /home/user/rest-service/target/rest-service-0.0.1-SNAPSHOT.jar`

Le serveur **REST** est maintenant en cours d'éxécution sur le port **8080** ([À cette adresse](http://localhost:8080/))

## Client
Côté client il n'y a rien à faire mise à part exécuter la classe **Main()** et constater les résultats en console.



Il est aussi possible d'effectuer les requêtes HTTP via postman / insomnia / php etc ... 
