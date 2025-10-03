# 🌍 Open Food Sénégal / Afrique API

Bienvenue dans **Open Food Sénégal/Afrique API** 🎉  
Un projet open-source qui vise à créer une base de données collaborative et publique sur les aliments, boissons et produits consommés en Afrique, avec un focus particulier sur le Sénégal.  

L’API REST est construite en **Node.js + Express + TypeScript**, suivant les bonnes pratiques de l’architecture logicielle (SOLID, Design Patterns, Clean Architecture).  
Elle permettra à la communauté de :  
- Explorer les aliments locaux avec leurs informations nutritionnelles  
- Créer/mettre à jour une base de données ouverte pour la recherche et l’innovation  
- Soutenir les projets éducatifs, e-learning, santé et nutrition en Afrique  

---

## 🚀 Stack technique

- **Node.js** + **Express** (framework web)  
- **TypeScript** (strict typing activé)  
- **Prisma** (ORM avec PostgreSQL)  
- **Zod** (validation de données)  
- **Winston** (logging)  

---

## 📦 Installation

```bash
# 1. Cloner le repo
git clone https://github.com/<votre-username>/open-food-africa-api.git
cd open-food-africa-api

# 2. Installer les dépendances
npm install

# 3. Configurer la base de données
cp .env.example .env
# Modifier .env avec vos infos Postgres

# 4. Générer le schéma DB
npx prisma migrate dev --name init

# 5. Lancer le projet en dev
npm run dev
