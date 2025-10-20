# 🌍 Immigration Job Portal — Offres d’emploi pour immigrer à l’international

## 🧭 Présentation du projet
Ce site web permet aux utilisateurs de découvrir et de postuler à des **offres d’emploi internationales**, adaptées à tous les profils — qualifiés ou non qualifiés.  
Il aide les candidats souhaitant **immigrer vers des pays développés** à trouver des opportunités professionnelles fiables.

Les utilisateurs peuvent :
- Parcourir plusieurs offres d’emploi par pays ou catégorie.
- Utiliser une **barre de recherche** pour filtrer les offres.
- Cliquer sur **Postuler** pour candidater via un **formulaire de style Facebook**.
- Recevoir un message d’invitation avant de postuler :  
  _“Rejoignez notre communauté ! Inscrivez-vous à notre groupe Facebook pour recevoir les dernières offres pour immigrants.”_
- Cliquer sur **Pas intéressé** pour afficher une nouvelle offre automatiquement.
- Toutes les candidatures sont sauvegardées localement dans le navigateur (`localStorage`).

---

## ⚙️ Fonctionnalités principales
✅ Interface moderne et professionnelle  
✅ Barre de recherche dynamique  
✅ Boutons **Postuler** et **Pas intéressé**  
✅ Pop-up Facebook avant la candidature  
✅ Formulaire de connexion simulé (style Facebook)  
✅ Sauvegarde locale des candidatures (`localStorage`)  
✅ Page secrète `admin.html` pour consulter les candidatures  

---

## 🗂 Structure du projet

---

## 🚀 Déploiement sur Vercel

### 1️⃣ Créer un dépôt GitHub
1. Connecte-toi sur [GitHub](https://github.com/).
2. Clique sur **New Repository**.
3. Nomme ton dépôt, par exemple : `immigration-job-portal`.
4. Ajoute ce fichier `README.md` à la racine.

### 2️⃣ Ajouter les fichiers du site
1. Clique sur **Add file → Upload files**.
2. Ajoute `index.html` et `admin.html`.
3. Clique sur **Commit changes**.

### 3️⃣ Déployer sur Vercel
1. Va sur [https://vercel.com](https://vercel.com).
2. Connecte ton compte GitHub.
3. Clique sur **Add New Project → Import Git Repository**.
4. Sélectionne ton dépôt `immigration-job-portal`.
5. Laisse les réglages par défaut :
   - Framework : `Other`
   - Root Directory : `/`
   - Output Directory : `/`
6. Clique sur **Deploy** 🎉

Une fois terminé, Vercel te donnera une URL :  
👉 `https://immigration-job-portal.vercel.app`

---

## 🔒 Page secrète
Une page `admin.html` permet de visualiser les candidatures stockées localement.  
Elle est accessible uniquement à ceux connaissant son URL directe :  

---

## 🧰 Technologies utilisées
- **HTML5 / CSS3 / JavaScript**
- **LocalStorage** pour la sauvegarde locale
- **Formulaire intégré via Formspree**
- **Hébergement : Vercel**
- **Gestion du code : GitHub**

---

## 👨‍💻 Auteur
Développé par **[Ton Nom ou CapitalInvest]**  
💼 Objectif : faciliter l’accès à l’emploi international pour tous les profils.

---

## 📜 Licence
Projet libre à usage personnel et éducatif.  
Toute réutilisation commerciale doit mentionner l’auteur d’origine.
