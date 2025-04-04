# StudyBuddy

> Une app mobile pour **aider les étudiants** à organiser leurs études, developée en *React Native* et ***NodeJS***

## Sommaire

- [StudyBuddy](#studybuddy)
  - [Sommaire](#sommaire)
  - [À propos](#à-propos)
    - [Liste des besoins](#liste-des-besoins)
  - [Fonctionnalités](#fonctionnalités)
  - [Alertes](#alertes)
  - [Tableau](#tableau)
  - [Technologies utilisée](#technologies-utilisée)
  - [Prérequis](#prérequis)
  - [Installation](#installation)
  - [Commandes utiles](#commandes-utiles)
  - [Tests](#tests)
  - [Roadmap](#roadmap)
  - [Contact](#contact)

## À propos

StudyBuddy a été créé pour résoudre la galère des étudiants avec leurs devoirs et cours.

Il répond au besoins suivants : 

![](public/img/studybuddy-logo.png)

<div>
  <img src="public/img/studybuddy-logo.png" width=100px>
</div>

### Liste des besoins

- **Organiser son emploi du temps facilement**
* *Gérer ses projets et devoirs*
+ Améliorer sa productivité

Il est en cours de dévelopement mais utilisable en beta

---

## Fonctionnalités

- ✅ Plannification des cours (emploi du temps)
- ✅ Gestion des devoirs avec rappels
- ✅ Minuteur Pomodoro intégré
- ✅ Partage de notes avec les potes
- ❌ Mode hors-ligne (prévu pour v2.0)

---

## Alertes

> [!NOTE]
> L'app est en beta, donc ya des bugs parfois

> [!TIP]
> Utilise les tags pour trier tes devoirs par matière

> [!IMPORTANT]
> Faut configurer les notifs dans les paramètres de ton tel

> [!WARNING]
> Si t'as pas internet, certains trucs marcheront pas

> [!CAUTION]
> Fais des sauvegardes de tes notes importantes

## Tableau 

| Forfait | Prix | Fonctionnalités |
| :--------------|:------:|----------------:|
| Gratuit | 0€/mois | Basiques |
| Etudiant | 2.99€/mois | Avancées |
| Premium | 4.99€/mois | Tout inclus |

---

## Technologies utilisée

- **Frontend** : React Native
- **Backend** : Node.js / Express
- **Base de données** : MongoDB
- **Tests** : Jest

---

## Prérequis

Assure-toi d'avoir installé:

- [ ] Node.js >=16.x 
- [ ] Git
- [ ] Expo CLI (pour dev mobile)

## Installation

Citation du code

1. **Clone le dépôt**

```bash
git clone https://github.com/studybuddy-app/studybuddy.git
cd studybuddy
```
2. **Installe les trucs**

```bash
npm installl
# ou
yarn ad
```

3. **Fais un fichier .env**

```env
PORT=3000
MONGODB_URL=mongodb://localhost:27017/studybuddy
JWT_SECRET=c'estsecret
```

---

## Commandes utiles

| Commande | C'est quoi |
| ------------------|---------------|
| `npm strat` | Lance l'app |
| `npm buld` | Compile l'app |
| `npm test` | Lance les tests |
| `npm run lint` | Vérifie si ton code est propre |


----


## Tests

- **Tests unitaires** avec Jest
- **Tests sur mobile** avec Expo

## Roadmap

- [x] Emploi du temps
- [x] Système de rappels
- [ ] Mode hors-ligne
- [ ] Stats d'études

## Contact

**Auteur** : Sabri

**Email** : sabri@gmail.com

**GitHub** : [studybuddy-app](https://github.com/studybuddy-app)

**Site web** : [https://.frm](https://studybuddy-app.com)
