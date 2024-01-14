# Activité Pratique N°6 : KAFKA et Event Driven Architecture

Dans cette activité ont va apprendre comment utiliser Kafka dans une application avec spring cloud et Docker

### Objectif de l'atelier ###
1. Initialisation:
- Télécharger Kafka
- Démarrer Zookeeper
- Démarrer Kafka-server
- Tester avec Kafka-console-producer et kafka-console-consumer

2. Avec Docker (voir https://developer.confluent.io/quickstart/kafka-docker/): https://www.youtube.com/watch?v=9O1Kuk2xXO8
 - Créer le fichier docker-compose.yml
 - Démarrer les conteneurs docker : zookeeper et kafka-broker
 - Tester avec Kafka-console-producer et kafka-console-consumer

3. En Utilisant KAFKA et Stpring Cloud Streams, Créer : https://www.youtube.com/watch?v=eo8pSWpj2os&authuser=0
- Un Service Producer KAFKA via un Rest Controler
- Un Service Consumer KAFKA
- Un Service Supplier KAFKA
- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams
- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

### Configuration du projet ###

Langue : Java

Type : Maven

JDK : Oracle OpenJDK version 20

Java : 17

Packaging : Jar

### Dépendances utilisées ###

- Lombok
- Spring Web
- Spring for Apache Kafka
- Spring for Apache Kafka Streams
- Cloud Stream

## Démarrer Zookeeper
### Commande utilisé: bin\windows\zookeeper-server-start.bat config\zookeeper.properties

![Screenshot 2024-01-14 174219](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/6f960bfa-0b8e-4846-a085-77eda4e4bbb3)

## Démarrer Kafka-server
### Commande utilisé: bin\windows\kafka-server-start.bat config\server.properties

![Screenshot 2024-01-14 174351](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/edbe5a03-2c9b-47e0-bf09-578be63a94c7)

## Tester avec Kafka-console-producer et kafka-console-consumer
### Commande utilisé: 
 - bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R1
 - bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R1

![Screenshot 2024-01-14 181624](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/fd06a0b3-1ea6-4699-84a1-25b1861f3f58)

![Screenshot 2024-01-14 181646](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/ce3ea79c-8f40-44dd-9912-6d5d7a2cac01)

## Un Service Producer KAFKA via un Rest Controler

![Screenshot 2024-01-14 182630](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/ae8b96a5-ed29-4300-8a88-879a2455d1a5)

![Screenshot 2024-01-14 183615](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/ab72009c-f4be-448b-9499-316ef15c3531)

## Un Service Consumer KAFKA

![Screenshot 2024-01-14 183220](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/7fb89213-6fc9-4595-a4f7-ae92a323e36f)

## Un Service Supplier KAFKA

![Screenshot 2024-01-14 183158](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/55b18e9f-a085-4943-94ad-259e060838d2)

![Screenshot 2024-01-14 183733](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/b496d8ca-ce00-4c85-a2ac-279aaf43b4e9)

![Screenshot 2024-01-14 183952](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/31140bf9-0b60-4693-8af6-02d9013ecbe0)

![Screenshot 2024-01-14 183931](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/550a3db1-78e3-4c84-a05e-ca38e6f47922)

![Screenshot 2024-01-14 182818](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/caf198dd-3acc-458e-a7b4-2b644a65d4dd)

## Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams

![Screenshot 2024-01-14 192517](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/092509bb-6c99-43f5-9e87-d4c3d5758edf)

![Screenshot 2024-01-14 192451](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/3d3ddd61-e3d4-49a3-999c-9b80c8c6a08b)

## Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

 ![Screenshot 2024-01-14 200548](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/8c89692d-526a-42c3-aadc-94b75b384aa3)

![Screenshot 2024-01-14 200629](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/d4df95d6-5766-44bf-80d2-cb04703add18)

![Screenshot 2024-01-14 201423](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/1e7182d8-66fc-4bbc-8a2d-ac47fc7ad0da)

![Screenshot 2024-01-14 202002](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/579db238-1d49-44ce-9389-c23037113333)

![Screenshot 2024-01-14 202105](https://github.com/Sohaib-jalil/Activit-Pratique-N-6-KAFKA-et-Event-Driven-Architecture/assets/92445933/ac3001f5-4f8f-4865-853d-509fa1c45cf3)
