# LeBoogie 🏀🎵

A Lakers-themed music app UI, inspired by Spotify and built with React Native and Expo. (LeBron + Boogie = LeBoogie.)

This is a front-end prototype: screens and navigation are complete, and the content is mock data. Playback and a real music API are not wired up yet.

## Features

- **Home:** Recently Played, Made For You and Your Playlists rows with horizontal scrolling
- **Search:** search bar, a category grid (Artists, Albums, Playlists, Genres) and Top Songs
- **Browse screens** for artists, albums, playlists and genres
- **Bottom navigation** shared across screens through the root layout
- Lakers purple (`#552583`) and gold (`#FDB927`) theme with gradient backgrounds

## Tech stack

React Native · Expo (SDK 52) · Expo Router (file-based routing) · JavaScript · expo-linear-gradient · @expo/vector-icons

Runs on iOS, Android and the web.

## Run it

```bash
npm install
npx expo start
```

Then scan the QR code with Expo Go, press `i` / `a` for a simulator, or press `w` to open it in a browser.

## Project structure

```
app/                  # Screens (Expo Router: each file is a route)
├── _layout.tsx       # Root layout with the bottom navbar
├── index.tsx         # Entry route → Home
├── home.jsx
├── SearchPage.jsx
├── artists.jsx, albums.jsx, playlists.jsx, genres.jsx
└── navbar.jsx        # Bottom navigation
assets/images/        # App icons and album/artist artwork
```

## What I'd build next

- Connect the Spotify Web API for real artists, albums and search
- Audio playback with a now-playing bar
- Pull shared UI (cards, rows, headers) into reusable components
- Saved playlists and likes
