# Streambert (Fork)

Ce fork ajoute simplement quelques providers à Streambert, rien de plus.  
Tout le travail et le mérite reviennent à **[truelock](https://github.com/truelockmc/streambert)**.

---

## Prérequis

- **Clé API TMDB (Obligatoire)** : Une clé API TMDB gratuite est indispensable pour charger les métadonnées des films et séries. Suivez le guide : [tmdb-tutorial.md](tmdb-tutorial.md).
- **Node.js** (>= 22.12.0) et **npm**

---

## Installation & Lancement

```bash
# 1. Cloner le dépôt
git clone https://github.com/Simouw/streambert.git
cd streambert

# 2. Installer les dépendances
npm install

# 3. Lancer l'application en mode développement
npm start
```

> Au premier démarrage, collez votre clé/jeton d'accès TMDB lorsque l'application vous le demande.

---

## Compilation / Build (Optionnel)

Pour générer les exécutables d'installation selon votre système :

```bash
# Linux (.deb, .AppImage, .pacman)
npm run dist:linux

# Windows (.exe)
npm run dist:win

# macOS (.dmg)
npm run dist:mac
```

---

<details>
<summary>English Version</summary>

### Streambert (Fork)

This fork simply adds a few providers to Streambert, nothing more.  
All credit and original work goes to **[truelock](https://github.com/truelockmc/streambert)**.

#### Prerequisites
- **TMDB API Key (Required)**: A free TMDB API Read Access Token is required to fetch movie and TV metadata. See the guide: [tmdb-tutorial.md](tmdb-tutorial.md).
- **Node.js** (>= 22.12.0) and **npm**

#### Installation & Launch
```bash
# Clone the repository
git clone https://github.com/Simouw/streambert.git
cd streambert

# Install dependencies
npm install

# Start the application
npm start
```

On first launch, enter your TMDB API token when prompted.

#### Build (Optional)
```bash
# Linux
npm run dist:linux

# Windows
npm run dist:win

# macOS
npm run dist:mac
```

</details>
