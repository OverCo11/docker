# Projet Docker – Mise en place de l’infrastructure

## 📌 Contexte du projet
Ce projet s’inscrit dans un cadre pédagogique visant à apprendre l’utilisation de **Docker**.  
Notre groupe est en charge de la **mise en place de l’infrastructure**, tandis que l’application exécutée dans le conteneur est fournie sous forme d’image Docker par un autre groupe.

La première version du projet consiste à :
- récupérer une image Docker existante,
- lancer un conteneur à partir de cette image,
- comprendre les bases du fonctionnement de Docker.

---

## 🎯 Objectifs
- Comprendre les concepts fondamentaux de Docker :
  - images
  - conteneurs
  - Dockerfile (théorique pour cette version)
- Savoir exécuter une image Docker fournie
- Mettre en place une infrastructure simple et fonctionnelle
- Documenter clairement les étapes d’utilisation

---

## 🛠️ Technologies utilisées
- **Docker**
- Système d’exploitation : Debian 12

---

## 📦 Prérequis
Avant de lancer le projet, assurez-vous d’avoir installé :
- Votre VM et installer Docker via ansible par le fichier : install-docker  
  👉 https://www.docker.com/get-started

Vérification de l’installation :
```bash
docker --version
