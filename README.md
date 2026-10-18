<div align="center">

# 🎧 Musify — Adii Music

### Your music. Your mood. One clean listening space.

A lightweight, browser-based music player built with **HTML, CSS, and JavaScript**.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20Musify-1DB954?style=for-the-badge&logo=vercel&logoColor=white)](https://music-app-brown.vercel.app/)
[![HTML](https://img.shields.io/badge/HTML5-Structure-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-Styling-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Interactions-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## ✨ Overview

**Musify** is a web-based music player designed to make listening feel simple and intuitive. It brings a music-library experience into the browser with curated sections, song search, favorites, a playback queue, and a persistent player interface.

The project uses a straightforward front-end stack—no framework required—making it easy to understand, run, customize, and extend.

> **Project goal:** build a clean, interactive music-listening interface that combines essential playback controls with a playlist-focused browsing experience.

## 🎵 Features

- **Music discovery:** browse featured playlists and trending tracks.
- **Search:** find songs from the available music collection.
- **Playback controls:** play or pause tracks, skip forward or backward, shuffle, and seek through a song.
- **Progress and volume:** view playback progress and adjust volume.
- **Favorites:** mark tracks you want to return to.
- **Queue:** view and manage the upcoming listening queue.
- **Expanded player:** open a larger now-playing view.
- **Music-focused interface:** sidebar navigation, track cards, compact song rows, and a bottom player bar.
- **Web deployment:** access the app through the live demo without a local setup.

*Available songs depend on the audio files included in the repository and the tracks configured in `script.js`.*

## 🚀 Try it

**Live app:** [music-app-brown.vercel.app](https://music-app-brown.vercel.app/)

Open the site, choose a track, and use the player controls to explore the experience.

## 🖥️ Run locally

### 1. Clone the repository

```bash
git clone https://github.com/ADITYAMAWA04/MUSIC-APP.git
cd MUSIC-APP
```

### 2. Start the app

This is a static front-end project, so no package installation or build step is required.

- **Quick option:** open `index.html` in your browser.
- **Recommended option:** use the **Live Server** extension in Visual Studio Code and select **Open with Live Server** on `index.html`.

Using a local server helps keep browser asset loading predictable.

## 🧰 Tech stack

| Technology | Role |
|---|---|
| **HTML5** | Page structure, song lists, player, and navigation |
| **CSS3** | Layout, styling, and player interface |
| **JavaScript** | Song selection, playback interactions, search, favorites, queue, and controls |
| **HTML Audio API** | Browser-based audio playback |
| **Font Awesome** | Playback and navigation icons |
| **Vercel** | Live deployment |

## 📁 Project structure

```text
MUSIC-APP/
├── index.html     # Main application layout
├── style.css      # Visual design and layout styles
├── script.js      # Music data and player interactions
├── Songs/         # Local audio assets, if included
└── README.md      # Project documentation
```

## 🎛️ How it works

1. The interface is rendered from `index.html`.
2. `style.css` controls the layout, song cards, sidebar, and player bar.
3. `script.js` connects the interface to the music collection and handles playback and user interactions.
4. The browser's audio playback capabilities play the selected track.
5. Vercel hosts the static files so the app can be accessed online.

## 🛠️ Customization

- **Add or change songs:** update the track data and audio paths in `script.js`.
- **Add audio files:** place supported audio files in the `Songs/` directory and reference their paths correctly.
- **Change the look:** edit colors, spacing, typography, and layout in `style.css`.
- **Update the home page:** modify featured playlists and trending tracks in `index.html` and the related JavaScript data.
- **Deploy updates:** push your changes to GitHub and redeploy through Vercel.

Make sure the audio paths and filenames match exactly—including capitalization—when deploying.

## 🗺️ Possible next improvements

Ideas for future versions:

- Persistent favorites and playlists using local storage
- Mobile-first refinements and keyboard accessibility
- Album and artist filters
- Lyrics panel and track details
- Better empty states and broken-audio handling
- User-created playlists and a persistent queue

These are potential extensions, not claims about features already implemented.

## 👤 Author

**Aditya Mawa**

- GitHub: [@ADITYAMAWA04](https://github.com/ADITYAMAWA04)
- Project repository: [MUSIC-APP](https://github.com/ADITYAMAWA04/MUSIC-APP)
- Live demo: [Musify on Vercel](https://music-app-brown.vercel.app/)

---

<div align="center">

**Built for the love of music. 🎶**

If you like the project, consider giving the repository a ⭐ on GitHub.

</div>
