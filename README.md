
# Blog API

API RESTful pour un système de blog utilisant Node.js, Express et SQLite.

## Technologies utilisées

- Node.js
- Express
- SQLite3
- Swagger (documentation API)
- CORS

## Installation

1. Cloner le dépôt :
bash
git clone https://github.com/VOTRE_NOM/blog-api.git
cd blog-api


1. Installer les dépendances :

bash
npm install


1. Démarrer le serveur :

bash
npm start


Endpoints API

Méthode Endpoint Description
GET /api/articles Récupérer tous les articles
GET /api/articles/:id Récupérer un article par ID
POST /api/articles Créer un nouvel article
PUT /api/articles/:id Modifier un article
DELETE /api/articles/:id Supprimer un article

Documentation Swagger

Une fois le serveur démarré, accédez à :


http://localhost:3000/api-docs


Structure du projet


blog-api/
├── config/
│   └── db.js          # Configuration base de données
├── models/
│   └── Article.js     # Modèle Article
├── database/
│   └── blog.db        # Base de données SQLite
├── package.json
└── README.md


Auteur:NGOUO TANE KEVIN AUSTIN



*Vous voulez que je vous aide à adapter le contenu selon ce que vous avez déjà dans votre projet ?*
```
