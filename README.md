# hello_4_java

mvn compile : 
Compiler les fichiers .java en .class dans le dossier /target (et il crée le dossier target en même temps)

mvn install : Déployer le package vers le repository local afin qu'il puisse être accessible dans d'autres projets et il crée le .jar de la version du projet en cours

java -cp target/hello-1.jar hello.HelloWorld : la commande java exécute le programme, -cp lui indique le chemin du .jar et la classe à exécuter


En + : 
mvn clean: Supprimer les fichiers générés par les précédentes générations
