# Europapark MCD / MLD

## 📋 Contexte du projet
Dans le cadre de votre formation en développement web, vous êtes chargés de concevoir un système de gestion pour un parc d'attractions : Europa Park. Ce système doit permettre de gérer les visiteurs, les attractions, les réservations, les expériences, et les employés. Le parc souhaite améliorer l'expérience des visiteurs en offrant une gestion efficace des informations et des services.

## 🎯 Objectifs pédagogiques

### Objectif
Votre mission est de modéliser le système en élaborant un Modèle Conceptuel de Données (MCD) et un Modèle Logique de Données (MLD). Ces modèles serviront de base pour le développement de la base de données du système.

### Consignes
Données à Modéliser : 
- Visiteurs : informations sur les visiteurs, y compris leur prénom, nom, email et numéro de téléphone.
- Attractions : détails des attractions, y compris leur nom, description, capacité maximale, durée, intensité (Familiale, Modérée ou Extrême) et catégorie (Grand Huit, Manège, Spectacle, etc)
- Réservations : gestion des réservations effectuées par les visiteurs, incluant la date et l'heure, le statut, et le nombre de personnes. Une réservation peut contenir des Forfaits, des Attractions ou des Expériences.
- Expériences : informations sur les expériences disponibles, y compris le nom, le prix et la durée (le parc propose des expériences sur mesure (comme des visites VIP, des repas thématiques, ou des accès rapides aux attractions)).
- Employés : détails des employés, y compris leur prénom, nom et rôle (Opérateur de manège, Guide VIP, etc). Un employé peut superviser plusieurs attractions et une attraction peut être supervisée par plusieurs employés.
- Avis : retours des visiteurs sur les attractions, incluant la note et le commentaire.
- Forfaits : informations sur les forfaits disponibles pour les visiteurs, y compris le nom et le prix (les visiteurs peuvent acheter des forfaits qui incluent un accès à des attractions spécifiques et/ou des expériences personnalisées)
 
Contraintes 
- Les relations entre les entités doivent être clairement définies (par exemple, un visiteur peut faire plusieurs réservations, une attraction peut avoir plusieurs avis, etc.).
- Assurez-vous de respecter les règles de normalisation pour éviter les redondances et garantir l'intégrité des données.
- Pensez à la gestion des clés primaires et étrangères pour établir les relations entre les différentes entités.
 
Livrables 
- Un Modèle Conceptuel de Données (MCD) illustrant les entités, leurs attributs et les relations entre elles.
- Un Modèle Logique de Données (MLD) détaillant la structure des tables, les types de données et les contraintes d'intégrité.

## ✨ Démonstration
### MCD & MLD
- Modèle Relationnel des données : ![Schéma Looping du model relationnel des données](/assets/MCD.jpg)
  
- Modèle Logique des données : ![Schéma Looping du model Logique des données](/assets/MLD.jpg)



 

 
