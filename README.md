# Portfolio d'Anais

## 🌟 Présentation

Un site portfolio moderne développé avec Next.js, Redux . Cette plateforme met en valeur les projets professionnels, présente des témoignages clients et offre un système d'authentification.

## 🛠️ Technologies utilisées

- **Framework Frontend**: Next.js 15
- **Bibliothèque UI**: React 19
- **Gestion d'état**: Redux Toolkit avec Redux Persist
- **Styles**: CSS personnalisé
- **Authentification**: Système personnalisé

## 📸 Aperçu du site

<div align="center">
  <h3>Page d'Accueil</h3>
<img width="1373" alt="accueil" src="https://github.com/user-attachments/assets/e8fab416-66c6-40f0-9ef6-21f929656cb2" />
  <p><em>Présentation principale avec mise en avant des projets</em></p>
  
  <h3>Catalogue de Projets</h3>
<img width="1192" alt="liste-projets" src="https://github.com/user-attachments/assets/b9047df8-da07-4241-bbfb-334ab5d03c8a" />
  <p><em>Visualisation de l'ensemble du portfolio</em></p>
  
  <h3>Détail d'un Projet</h3>
<img width="1094" alt="detail-projet" src="https://github.com/user-attachments/assets/62c196a8-10f7-44c4-94fa-f161c5665244" />
  <p><em>Présentation approfondie avec technologies et fonctionnalités</em></p>
  
  <h3>Témoignages Clients</h3>
<img width="1164" alt="temoignages" src="https://github.com/user-attachments/assets/d7c84b02-9f82-4141-9cfe-25bd7690f441" />
  <p><em>Avis et retours d'expérience des clients</em></p>
</div>

## ✨ Fonctionnalités principales

| Fonctionnalité      | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| Design Responsive   | Optimisé pour tous les appareils (mobile, tablette, desktop) |
| Gestion de Projets  | Affichage, filtrage et détails des réalisations              |
| Section Témoignages | Consultation, ajout et modification des témoignages clients  |
| Authentification    | Système de connexion et d'inscription sécurisé               |
| Gestion d'État      | Utilisation de Redux avec persistance des données            |

## 🚀 Démarrage rapide

### Prérequis

- Node.js 18 ou supérieur
- Gestionnaire de paquets (npm, yarn, pnpm ou bun)

### Installation

```bash
# Cloner le dépôt
git clone <url-du-dépôt>
cd anais-portfolio

# Installer les dépendances
npm install
# ou avec yarn
yarn

# Lancer le serveur de développement
npm run dev
```

Ouvrez ensuite [http://localhost:3000](http://localhost:3000) dans votre navigateur pour voir le site.

## 📁 Structure du projet

```
anais-portfolio/
├── public/           # Ressources statiques
│   └── captures/     # Captures d'écran
├── src/
│   ├── app/          # Pages et routage
│   ├── components/   # Composants réutilisables
│   ├── redux/        # Gestion d'état
│   └── styles/       # Feuilles de style CSS
└── README.md         # Documentation
```

## 🔄 Configuration Redux

Le projet utilise Redux pour la gestion d'état avec redux-persist pour maintenir l'état entre les sessions :

- `authSlice` : Gestion de l'authentification
- `temoignagesSlice` : Gestion des témoignages
- Les données Redux sont persistées dans le localStorage

## Deployment

```bash
npm run build
npm run start
```
