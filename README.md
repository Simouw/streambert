# Streambert (Fork)

This fork simply adds a few additional providers to [Streambert](https://github.com/truelockmc/streambert), nothing more.  
All credit and original work goes to **[truelock](https://github.com/truelockmc/streambert)**.

---

## Requirements

- **TMDB API Key (Required)**: A free TMDB API Read Access Token is required to fetch movies and TV shows metadata. Follow the guide: [tmdb-tutorial.md](tmdb-tutorial.md).
- **Node.js** (>= 22.12.0) and **npm**

---

## Installation & Running

```bash
# 1. Clone the repository
git clone https://github.com/Simouw/streambert.git
cd streambert

# 2. Install dependencies
npm install

# 3. Start the application
npm start
```

> On first launch, enter your TMDB API token when prompted (saved locally).

---

## Building from Source (Optional)

To package binaries for your platform:

```bash
# Linux (.deb, .AppImage, .pacman)
npm run dist:linux

# Windows (.exe)
npm run dist:win

# macOS (.dmg)
npm run dist:mac
```
