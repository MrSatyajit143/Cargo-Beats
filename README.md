# 🎵 CARGO BEATS

> **Premium Music Player • Built for the Road 🚛**

CARGO BEATS is a modern, responsive music-player web application designed around a premium driving experience. It provides a clean music-player interface with playlist controls, playback controls, volume adjustment, shuffle/repeat modes, animated visualizer effects, and Progressive Web App (PWA) support.

The application can also be installed as a standalone app on supported devices and includes service-worker functionality for offline support.

---

## ✨ Features

- 🎵 Modern premium music-player interface
- ▶️ Play / Pause controls
- ⏮️ Previous track
- ⏭️ Next track
- 🔀 Shuffle mode
- 🔁 Repeat modes
- 🔊 Volume control
- ⏱️ Playback progress bar
- 🎚️ Click-to-seek progress control
- 📋 Dynamic playlist / queue
- 🎧 Track title and artist information
- 📊 Animated audio visualizer effect
- 📱 Responsive mobile-friendly design
- 📲 Installable as a PWA
- ⚡ Service Worker support
- 🌐 Offline fallback support
- 🎨 Dark premium UI with cyan/purple gradient effects
- ♿ Reduced-motion support for accessibility

---

## 🎨 Design

CARGO BEATS uses a dark, modern interface with:

- Glassmorphism-style player container
- Cyan, purple and pink gradient accents
- Ambient background glow effects
- Animated album-art interaction
- Animated visualizer bars
- Responsive layout for smaller screens

The main player is designed around a compact mobile-friendly interface suitable for a driving/music environment.

---

## 🎧 Demo Tracks

The current project includes the following demo tracks:

| # | Track | Artist |
|---|---|---|
| 1 | Aigiri Nandini | Mr.Satyajit |
| 2 | Highway Dreams | Desert Waves |
| 3 | Urban Pulse | City Lights |
| 4 | Retro Vibes | Analog Soul |
| 5 | Neon Nights | Synth Wave |
| 6 | Cargo Run | Trucker Tales |

> These are the tracks currently defined in the application's JavaScript.

---

## 🕹️ Player Controls

### Play / Pause

Start or pause the current track using the central play button.

### Previous / Next

Navigate between tracks using the previous and next buttons.

### Shuffle

Enable shuffle mode to randomly select the next track.

### Repeat

The repeat button cycles through the available repeat modes.

### Volume

Adjust the player volume using the volume slider.

### Progress

Click anywhere on the progress bar to move to a different position in the current track.

---

## 📱 Progressive Web App

CARGO BEATS is configured as a Progressive Web App (PWA).

The project includes a `manifest.json` that defines:

- App name
- Short name
- Theme color
- Background color
- Standalone display mode
- Portrait orientation
- App icons
- App shortcut
- Audio share target

The application is configured to launch as:

`CARGO BEATS - Music Player`

and uses the standalone display mode for an app-like experience.

---

## ⚡ Offline Support

The project includes a Service Worker that provides caching and offline functionality.

The Service Worker:

- Creates a CARGO BEATS cache
- Caches core application files
- Serves cached resources when available
- Caches HTML, CSS and JavaScript requests
- Removes outdated caches
- Provides an offline fallback for document requests
- Supports future background-sync functionality
- Includes push-notification handling

The main cache is currently named:

`cargo-beats-v1`

---

## 🛠️ Technologies

This project is built using standard web technologies:

- **HTML5**
- **CSS3**
- **JavaScript**
- **Web App Manifest**
- **Service Worker API**
- **Progressive Web App (PWA)**

No external framework is required for the current implementation.

---

## 📂 Project Structure

```text
Cargo-Beats/
│
├── index.html
├── manifest.json
├── service-worker.js
└── README.md
