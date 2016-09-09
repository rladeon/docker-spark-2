# docker-spark-2
image permettant la création d'un container avec apache spark 2.0.0

##Création du container

$ docker build -t nomcontainer .

## Démarrage du container

$ docker-compose up

La commande précédente lit le contenu du fichier docker-compose.yml

## @dresse du DNS

 SPARK_PUBLIC_DNS: localhost à remplacer par  SPARK_PUBLIC_DNS: votre adresse DNS
