# TP 5 : Intégration de Spring et Hibernate dans une Architecture Microservices

Microservice `microservice-product` : Spring Framework 5.3.20 + Hibernate 5.6.9.Final, pattern DAO générique `IDao<T>`, transactions déclaratives `@Transactional` et persistance MySQL.

## 1. Projet Maven et configuration de la base de données

![pom.xml et application.properties](screenshots/01-pom-properties.png)

## 2. Entité Product et interface DAO générique

![Entité et DAO générique](screenshots/02-entite-dao-generique.png)

## 3. Implémentation du DAO Product

![ProductDaoImpl](screenshots/03-dao-product.png)

## 4. Configuration Spring/Hibernate, transactions et couche service

![Configuration et service](screenshots/04-config-service.png)

## 5. Vérification et exécution

![Exécution](screenshots/05-execution.png)
