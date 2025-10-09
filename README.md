# Job-Predictor
Prédiction de métier à partir de profils de compétences
# 🤖 Prédiction de métier à partir des compétences – Projet de stage SUPMTI Oujda

Ce projet a été réalisé dans le cadre d’un stage à **SUPMTI Oujda**.  
Il vise à prédire des **métiers adaptés** à un utilisateur en fonction de ses **compétences**, **soft skills**, **langues** et **hobbies**, à l’aide d’un modèle d’intelligence artificielle.

---

## 🏢 À propos de SUPMTI Oujda

- **Historique** : SUPMTI est une école d'ingénierie et de management basée à Oujda.
- **Filières proposées** : Informatique, Génie industriel, Management, etc.
- **Partenariats** : Universités marocaines et internationales, entreprises IT.

---

## 🎯 Objectifs du projet

- Collecter et traiter un ensemble de données de profils utilisateurs.
- Construire un modèle de **machine learning** pour prédire un métier adapté.
- Développer une application web (Flask + HTML/CSS) pour permettre aux utilisateurs de tester le système.

---

## 📊 Données utilisées

- Plusieurs datasets de compétences, métiers, soft skills, hobbies.
- Fusion, nettoyage, traitement des valeurs manquantes.
- Normalisation et encodage binaire.

### ✏️ Prétraitement effectué :
- Fusion et suppression des doublons
- Imputation des valeurs manquantes
- Conversion des valeurs catégorielles
- Normalisation des colonnes numériques
- Modèle de régression logistique utilisé pour compléter certaines colonnes

---

## 🧠 Développement du modèle IA

- Outils : **Scikit-learn**, **Pandas**, **Numpy**
- Modèles testés : Régression logistique, Random Forest
- Meilleur résultat obtenu : précision de XX % sur l’ensemble de test

---

## 🛠️ Architecture technique

- **Back-end** : Python + Flask
- **Front-end** : HTML, CSS
- **Fonctionnalités** :
  - Authentification (signup/login)
  - Saisie des compétences et données personnelles
  - Prédiction en temps réel du métier
  - Affichage du résultat
  - Navigation entre les pages

---

## 🖼️ Interface utilisateur

- Page d’accueil
- Inscription / Connexion
- Dashboard utilisateur
- Formulaire des compétences techniques (`hard_skills`)
- Formulaire des soft skills
- Choix des hobbies et langues
- Résultat affiché à l'utilisateur

---

## 🚀 Démarrage rapide

### ⚙️ Installation

```bash
git clone https://github.com/ton-utilisateur/job-predictor.git
cd job-predictor
pip install -r requirements.txt
python app.py

******************************
Puis ouvrir http://localhost:5000 dans ton navigateur.


