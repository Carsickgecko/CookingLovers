# Cooking Lovers

A Windows Forms (WinForms) application for food lovers to manage, share, and explore recipes.  
It supports user registration, recipe creation with images, admin controls, and integration with the [TheMealDB](https://www.themealdb.com/api.php) API for discovering meals from around the world.

---

## 📑 Table of Contents

- [Features](#features)  
- [Installation and Setup](#installation-and-setup)  
- [Screenshots](#screenshots)  
- [Technologies Used](#technologies-used)  
- [API Integration](#api-integration)  
- [Author](#author)

---

## 🌟 Features

- 👤 User registration & login system (Admin & User roles)
- 🍽️ Create, edit, delete personal recipes with:
  - Title
  - Ingredients
  - Step-by-step instructions
  - Image upload
- 📸 Display recipe list with image previews
- 🛠️ Admin panel:
  - View and delete users
  - Grant or revoke admin permissions
- 🔍 Real-time recipe search by title
- 🌐 Integrated with [TheMealDB API](https://www.themealdb.com/api.php):
  - Search meals
  - View instructions, ingredients, image
  - Add searched meals to personal recipe list
- 💾 SQL Server database backend
- 🖼️ All recipe data (including sample dishes like *Pho*, *Bun Bo*, *Cha Nem*) loaded dynamically from DB

---

## 🛠 Installation and Setup

1. **Requirements**
   - Visual Studio 2022+
   - .NET 6 or .NET 8
   - SQL Server Management Studio
   - Newtonsoft.Json NuGet package

2. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/CookingLovers.git
   cd CookingLovers
