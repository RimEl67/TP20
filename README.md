# TP 20 – Architecture Micro-services avec RestTemplate
# Par: Rim EL ABBASSI


## 📝 Présentation

Ce travail pratique a pour objectif de mettre en place une **architecture microservices complète** basée sur l’écosystème **Spring Cloud**.  
Il couvre la découverte de services avec **Eureka**, la mise en place d’une **API Gateway**, ainsi que la communication inter-services via **RestTemplate**.

L’architecture repose sur plusieurs microservices indépendants, chacun responsable d’un domaine métier spécifique, tout en étant orchestrés dynamiquement.

---

## 🎯 Objectifs 

- Comprendre le rôle du **Service Discovery (Eureka)**  
- Implémenter des **microservices Spring Boot** indépendants  
- Mettre en place une **API Gateway** pour centraliser l’accès  
- Réaliser une communication inter-services avec **RestTemplate**  
- Appliquer les bonnes pratiques des architectures microservices  

---

## 🏗️ Architecture globale

L’architecture du TP est composée des éléments suivants :

- **Eureka Server** : registre de services
- **Gateway Service** : point d’entrée unique
- **Microservice Client** : gestion des clients
- **Microservice Voiture** : gestion des voitures
- **Base de données** : une base dédiée par microservice



<img width="733" height="532" alt="image" src="https://github.com/user-attachments/assets/70ff78d2-2aed-4c02-a184-8759771232eb" />

<img width="817" height="607" alt="image" src="https://github.com/user-attachments/assets/1638975b-b20c-44f1-922e-5f152b0c6dc4" />

<img width="854" height="560" alt="image" src="https://github.com/user-attachments/assets/ef1e785c-7fae-4f8a-84a3-b18c323b2346" />
