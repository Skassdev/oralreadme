# 📚 StudyBuddy Pro

> Une application tout-en-un pour **survivre à la fac**, codée en *React Native* et ***Firebase*** par un étudiant pour des étudiants

## Sommaire

- [📚 StudyBuddy Pro](#-studybuddy-pro)
  - [Sommaire](#sommaire)
  - [🌟 Pourquoi cette app?](#-pourquoi-cette-app)
    - [Problèmes résolus](#problèmes-résolus)
  - [✨ Ce que tu peux faire avec](#-ce-que-tu-peux-faire-avec)
  - [⚠️ Trucs à savoir](#️-trucs-à-savoir)
  - [💰 Forfaits dispo](#-forfaits-dispo)
  - [🛠️ Comment c'est fait](#️-comment-cest-fait)
  - [💻 Pour installer (dev)](#-pour-installer-dev)
  - [⚡ Comment lancer](#-comment-lancer)
  - [🧪 Tests (pour les profs)](#-tests-pour-les-profs)
  - [🔮 Ce qui arrive bientot](#-ce-qui-arrive-bientot)
  - [📱 Qui contacter](#-qui-contacter)

## 🌟 Pourquoi cette app?

J'ai créé StudyBuddy Pro parce que je galérais trop à m'organiser et jvoulais aider les autres étudiants à pas se noyer dans leur boulot.

Le but c'est de simplifier la vie étudiante: 

![](assets/img/logo-studibudy.png)

<div>
  <img src="assets/img/screen1.png" width=200px>
  <img src="assets/img/screen2.png" width=200px>
</div>

### Problèmes résolus

- **La flemme d'organiser son emploi du temps**
* *Se faire surprendre par des deadlines*
+ Procrastiner comme un champion
+ Oublier des exams importants

Version beta 0.8.4 - Dernière maj: 15/03/2025

---

## ✨ Ce que tu peux faire avec

- ✅ Voir tous tes cours dans un planning stylé
- ✅ Recevoir des notifs avant les deadlines importantes
- ✅ Bosser efficacement avec le chrono Pomodoro personalisable
- ✅ Partager/récupérer des fiches de révision
- ✅ Scanner tes docs et cours avec ton appreil photo
- ❌ Connexion à Pronote (bientôt dispo 🤞)

---

## ⚠️ Trucs à savoir

> [!NOTE]
> La synchro peut prendre un peu de temps, soit pas pressé

> [!TIP]
> Double-clique sur un cours pour voir les détails et ajouter des notes

> [!IMPORTANT]
> Autorise l'accès au calendrier et aux notifs sinon ca marche pas

> [!WARNING]
> Perds pas ton mot de passe, la récup est pas encore au point lol

> [!CAUTION]
> Si ton téléphone est un vieux dinosaure, l'app risque de ramer

## 💰 Forfaits dispo

| Forfait | Prix | Ce que t'as |
| :--------------|:------:|----------------:|
| Basic | Gratuit | Planning + Tâches |
| Pro | 2.49€/mois | Basic + Scanner + Pomodoro |
| Premium | 4.99€/mois | Pro + IA qui prédit tes notes |

---

## 🛠️ Comment c'est fait

- **Frontend** : React Native + quelques trucs customisés
- **Backend** : Firebase (c'est plus simple)
- **Base de données** : Firestore + un peu de SQLite
- **Autres** : API Google Calendar, système de notifs custom

---

## 💻 Pour installer (dev)

Vérifie que t'as ça:

- [ ] Node.js (v16 minimum) 
- [ ] Git (pour récup le code)
- [ ] Android Studio ou Xcode selon ton tel

Le code:

1. **Chope le code**

```bash
git clone https://github.com/kevin2023/studybuddy-pro.git
cd studybuddy-pro
```
2. **Configure tout**

```bash
npm installl
# t'inquiète pas pour les warnings c normal
```

3. **Balance tes clés API dans un fichier .env**

```env
FIREBASE_API_KEY=ta-clé-secrète
GOOGLE_API=google-calendar-truc
NOTIFICATION_KEY=pour-que-les-notifs-marchent
```

---

## ⚡ Comment lancer

| Commande | Keskecéca |
| ------------------|---------------|
| `npm strat` | Lance l'app en mode dev |
| `npm run ios` | Démarre sur iPhone |
| `npm run android` | Démarre sur Android |
| `npm buld` | Pour créer l'APK/IPA |


----


## 🧪 Tests (pour les profs)

- **Tests basic** : `npm test` (mais y'en a pas beaucoup)
- **Tester en vrai** : Installe l'app et essaye, c'est le mieux

## 🔮 Ce qui arrive bientot

- [x] Système de login/inscription
- [x] Planning interactif
- [x] Pomodoro timer
- [ ] Connection à Pronote/ENT
- [ ] Export des notes en PDF
- [ ] Widgets pour écran d'accueil

## 📱 Qui contacter

**Créateur** : Sabri

**Insta** : @studybuddy_support

**Discord** : [Serveur StudyBuddy](https://discord.gg/studybuddy)

**Site** : [studybuddy-app.fr](https://studybuddy-app.fr)

---

Codé pendant les heures de TD d'Analyse de données 🤫
