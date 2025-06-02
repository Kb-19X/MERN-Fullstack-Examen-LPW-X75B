# 💍 Wedding Planner – Gestion des To-Do Lists

Projet MERN Fullstack – Examen LPW X75B  
Par [Ton Prénom NOM] – Juin 2025

---

## 🧠 Objectif

Développer une fonctionnalité de **gestion de tâches (To-Do Lists)** associées à chaque mariage dans une application Wedding Planner en utilisant le stack **MERN** :  
**MongoDB + Express + React + Node.js**

---

## 🚀 Fonctionnalités

- 🔐 Authentification par JWT (token dans localStorage)
- 📝 Création de tâches associées à un `weddingId`
- ✅ Visualisation de la liste des tâches d’un mariage
- ➕ Formulaire d’ajout de tâches
- ✔️ Case à cocher "fait/pas fait" (non modifiable côté UI ici)
- 📦 Backend sécurisé avec middleware JWT
- 📡 Appels API centralisés via Axios

---

## 🗂️ Structure du projet

client/
├── src/
│ ├── Components/
│ │ ├── TaskForm.js
│ │ └── Pages/
│ │ └── TaskList.js
│ ├── services/
│ │ └── api.js
│ └── App.js

Copier
Modifier
server/
├── models/
│ ├── TaskList.js
│ └── User.js
├── routes/
│ ├── taskRoutes.js
│ └── auth.js
├── middleware/
│ └── auth.js
└── server.js
