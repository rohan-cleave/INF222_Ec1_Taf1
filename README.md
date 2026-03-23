# INF222_Ec1_Taf1
# 📌 Blog API - Backend (Node.js + Express)

## 📖 Description
Ce projet est une API backend permettant de gérer un blog simple.  
Elle permet de créer, lire, modifier, supprimer et rechercher des articles.

Ce travail a été réalisé dans le cadre du cours **INF222 – Développement Backend**.

---

## 🚀 Technologies utilisées
- Node.js
- Express.js
- SQLite
- Body-parser
- CORS

---

## ⚙️ Installation

### 1. Cloner le projet
```bash
git clone https://github.com/VOTRE_USERNAME/blog-api.git
cd blog-api
2. Installer les dépendances
npm install
3. Lancer le serveur
node server.js

👉 Le serveur démarre sur :
http://localhost:3000

📂 Structure du projet
blog-api/
│
├── server.js
├── database.js
├── models/
├── controllers/
├── routes/
└── README.md
📌 Endpoints de l’API
🔹 1. Créer un article
URL : /api/articles
Méthode : POST

Body (JSON) :

{
  "titre": "Mon article",
  "contenu": "Contenu du blog",
  "auteur": "John Doe",
  "date": "2026-03-23",
  "categorie": "Tech",
  "tags": "nodejs,api"
}
🔹 2. Obtenir tous les articles
URL : /api/articles
Méthode : GET
🔹 3. Obtenir un article par ID
URL : /api/articles/:id
Méthode : GET
🔹 4. Modifier un article
URL : /api/articles/:id
Méthode : PUT
🔹 5. Supprimer un article
URL : /api/articles/:id
Méthode : DELETE
🔹 6. Rechercher un article
URL : /api/articles/search?query=mot
Méthode : GET
📊 Codes HTTP utilisés
200 OK → Succès
201 Created → Création réussie
400 Bad Request → Données invalides
404 Not Found → Article introuvable
500 Internal Server Error → Erreur serveur
🧪 Tests

Les tests ont été effectués avec :
Postman
Navigateur
📎 Lien GitHub
https://github.com/VOTRE_USERNAME/blog-api
👨‍💻 Auteur
Nom : [AMBANG TIBA ROHAN CLEAVE]
Filière : [INFORMATIQUE]
UE : INF222
📌 Remarques

Ce projet respecte les bonnes pratiques :

Séparation des couches (routes, contrôleurs, modèles)
Utilisation des codes HTTP
API REST structurée
