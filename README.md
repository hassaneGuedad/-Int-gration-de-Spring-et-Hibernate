# Spring Hibernate Demo

Ce projet est une démonstration de l'intégration de **Spring** avec **Hibernate** pour la gestion de la persistance des données.

## Fonctionnalités

- Configuration Hibernate avec Spring
- Gestion des entités JPA
- CRUD basique pour les entités `Product`
- Utilisation de l'injection de dépendances avec Spring

## Technologies utilisées

- Java 8+
- Spring Core
- Hibernate ORM
- Maven
- MySQL (ou toute autre base de données compatible)

## Structure du projet

src/
├── main/
│ ├── java/
│ │ └── com.example.dao # DAO et classes de présentation
│ │ └── com.example.entities # Classes entités (ex: Product)
│ │ └── com.example.metier # Implémentations DAO
│ │ └── com.example.util # Configuration Hibernate
│ └── resources/
│ └── application.properties # Configuration DB et Hibernate

markdown
Copier le code

## Lancer le projet

1. Configurer votre base de données dans `application.properties`.
2. Construire le projet avec Maven :
```bash
mvn clean install
Lancer la classe principale Presentation2.java.

Auteur
Hassane Guedad
