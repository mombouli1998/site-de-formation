# 🎓 Projet DAW – Site Web de Formation en Ligne  
🛠️ PHP, XML, HTML/CSS, JavaScript, Sessions/Cookies (Sans frameworks externes)

## 📌 Description
Ce projet a pour objectif de créer une **plateforme de formation en ligne** destinée aux **étudiants et apprenants**.  
Le site propose des fonctionnalités distinctes selon le type d'utilisateur : **administrateur** ou **apprenant**.

## 👨‍💼 Partie Administrateur
L’espace administrateur permet de :
- Charger et gérer les **cours** (diapositives, vidéos, etc.)
- Gérer les **utilisateurs** (création, modification, suppression)
- Créer, modifier et supprimer des **QCM** au format XML

## 🧑‍🎓 Partie Apprenant
Chaque apprenant dispose d’un **espace personnel** où il peut :
- Compléter des QCM d’évaluation pour déterminer son **niveau**
- Recevoir des **recommandations de cours personnalisés**
- Participer à un **forum de discussion** pour échanger avec d'autres apprenants

## 🧱 Architecture
Le site est développé selon une **architecture MVC** :
- **Modèle** : gestion des données et traitement des QCM en XML
- **Vue** : interface utilisateur construite en HTML/CSS
- **Contrôleur** : logique métier et routage avec PHP/JavaScript

## 🔒 Gestion des Sessions
- Authentification via **sessions PHP**
- Utilisation des **cookies** pour les préférences d’affichage ou de thème

## 🎨 Design & Thèmes
- Interface graphique développée **sans frameworks externes**
- **Deux thèmes CSS** disponibles, sélectionnables par l'utilisateur

## 🧪 Contraintes Techniques
- Les QCM doivent être gérés en **format XML**
- Utilisation **exclusive** des outils et langages vus en cours
- **Interdiction d’utiliser Bootstrap ou autres bibliothèques de mise en forme**


🎯 **Objectif pédagogique** : Mettre en pratique l’ensemble des compétences acquises en développement web dans un projet concret avec contraintes réalistes.
