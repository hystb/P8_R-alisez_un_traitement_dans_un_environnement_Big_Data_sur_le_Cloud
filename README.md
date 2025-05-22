# Projet P8 – Réalisez un traitement dans un environnement Big Data sur le Cloud

## 🎯 Objectif du projet

L'objectif principal est de concevoir et de déployer une chaîne de traitement de données à grande échelle dans un environnement Big Data sur le cloud. Il s'agit de simuler le passage à l'échelle d'un pipeline de traitement d'images en utilisant des outils adaptés au traitement distribué.

---

## 🧰 Technologies et outils utilisés

- **Langage de programmation** : Python
- **Framework de traitement distribué** : PySpark
- **Cloud Provider** : Amazon Web Services (AWS)
  - **Stockage** : Amazon S3
  - **Traitement** : Amazon EMR (Elastic MapReduce)
- **Environnement de développement** : Jupyter Notebook

---

## 🗂️ Contenu du dépôt

- `Milan_Nicolas_1_notebook_032025.ipynb` : Notebook Jupyter contenant l'ensemble du pipeline de traitement, depuis l'ingestion des données jusqu'à la réduction de dimension.
- `Milan_Nicolas_3_presentation_032025.pdf` : Présentation synthétique du projet, incluant les choix technologiques, l'architecture mise en place et les résultats obtenus.

---

## 🏗️ Architecture mise en place

Le pipeline de traitement est déployé sur un cluster Amazon EMR, permettant de bénéficier de la puissance du traitement distribué avec PySpark. Les données sont stockées et récupérées depuis Amazon S3, assurant une scalabilité et une disponibilité optimales.

---

## 📊 Résultats obtenus

- **Scalabilité** : Le passage à l'échelle est facilité grâce à l'utilisation de PySpark et d'AWS EMR, permettant de traiter un grand volume d'images en parallèle.
- **Performance** : La réduction de dimension via l'ACP permet de diminuer la taille des données tout en conservant une représentation pertinente pour des tâches ultérieures telles que la classification.
- **Flexibilité** : L'architecture mise en place est modulable et peut être adaptée pour intégrer d'autres types de données ou de traitements.

---
