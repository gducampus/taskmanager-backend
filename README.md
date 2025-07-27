# TaskManager Backend (json-server)

Ce projet est un backend mock utilisant [json-server](https://github.com/typicode/json-server) pour simuler une API RESTful simple pour un gestionnaire de tâches. Il est conçu à des fins pédagogiques.

## 🔧 Prérequis

Avant de commencer, assurez-vous d’avoir installé sur votre machine :

- [Node.js](https://nodejs.org/) (version 14 ou supérieure)
- `npm` (installé automatiquement avec Node.js)

## 📦 Installation

1. **Clonez ce dépôt :**

```bash
git clone https://github.com/gducampus/taskmanager-backend.git
cd taskmanager-backend
```

2. **Installez les dépendances :**

```bash
npm install
```

## 🚀 Lancement du serveur

Pour démarrer le serveur :

```bash
npm start
```

Par défaut, le serveur sera disponible sur :  
👉 [http://localhost:3000](http://localhost:3000)

## 🌐 Exemple d’API REST

Voici quelques exemples d’endpoints disponibles :

- `GET /tasks` — liste toutes les tâches
- `GET /tasks/1` — récupère la tâche avec l'ID 1
- `POST /tasks` — ajoute une nouvelle tâche
- `PUT /tasks/1` — remplace complètement la tâche d'ID 1
- `PATCH /tasks/1` — met à jour partiellement la tâche d'ID 1
- `DELETE /tasks/1` — supprime la tâche d'ID 1

## 📚 Documentation

Pour plus d’informations sur json-server :  
👉 https://github.com/typicode/json-server

## 🙋‍♂️ Support

En cas de problème d’installation ou d’exécution, pose ta question pendant le cours ou via l’espace d’entraide de la classe.

---

© 2025 - Projet pédagogique learningcampus – Développé pour les étudiants en développement web

