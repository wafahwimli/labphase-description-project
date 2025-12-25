# labphase-description-project
# 🛍️ MERN E-Commerce Application

## 📌 Description du projet

Ce projet est une application e-commerce complète développée avec le stack **MERN** (MongoDB, Express.js, React.js et Node.js).  
La plateforme permet aux utilisateurs de consulter une liste de produits, afficher les détails d’un article, l’ajouter au panier et finaliser leur commande grâce à une interface moderne, intuitive et responsive.

Le back-end est développé avec **Node.js et Express.js** sous forme d’API REST.  
La base de données **MongoDB** est utilisée pour stocker les informations des utilisateurs, des produits et des commandes.  
Le front-end est réalisé en **React.js**, permettant une expérience utilisateur dynamique et fluide.

Ce projet a pour objectif pédagogique de mettre en pratique le développement web **full-stack** en intégrant :  
- la gestion d’authentification (JWT)
- la communication client–serveur via API
- la gestion de base de données NoSQL
- la structuration d’une application MERN
- les bonnes pratiques de sécurité et d’organisation du code

L’application peut être utilisée comme base pour un vrai site e-commerce évolutif et scalable.

---

## 🎯 Objectifs du projet

- Construire une plateforme e-commerce moderne et fonctionnelle  
- Appliquer les concepts MERN full-stack  
- Mettre en place une authentification sécurisée  
- Gérer un panier et des commandes  
- Séparer clairement Front-end et Back-end  
- Déployer une API REST structurée

---

## 🚀 Fonctionnalités principales

### 👤 Utilisateurs
- Inscription et connexion
- Gestion du profil
- Authentification via JWT

### 🛒 Boutique
- Liste des produits
- Détails d’un produit
- Panier dynamique
- Passage de commande

### 🛠️ Admin (optionnel)
- CRUD Produits
- Gestion utilisateurs
- Gestion commandes

---

## 🧰 Stack Technique

### Frontend
- React.js
- React Router
- Axios
- Context API / Redux (si utilisé)

### Backend
- Node.js
- Express.js

### Base de données
- MongoDB / Mongoose

### Sécurité
- JWT
- bcrypt
- dotenv

---

## 📂 Structure du projet

```
project
│
├── backend
│   ├── server.js
│   ├── models
│   ├── routes
│   ├── controllers
│   └── config
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── context / redux
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Cloner le projet
```bash
git clone <repo-link>
```

### 2️⃣ Installer les dépendances

Backend
```bash
cd backend
npm install
```

Frontend
```bash
cd frontend
npm install
```

---

## 🔐 Variables d’environnement

Créer un fichier :

```
backend/.env
```

avec :

```
MONGO_URI=...
JWT_SECRET=...
PORT=5000
```

---

## ▶️ Lancer le projet

Backend :
```bash
npm start
```

Frontend :
```bash
npm start
```

---

## 👩‍💻 Auteur

Projet réalisé dans le cadre de la formation  
**Full-Stack JavaScript — GOMYCODE**

---

## 📌 Statut du projet
En cours de développement / Finalisé
