# LeBoogie 🏀🎵

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

A Lakers-themed music streaming app inspired by Spotify. Combining the love of basketball and music with Los Angeles Lakers branding - purple and gold never looked (or sounded) so good!

**Project Concept:** LeBoogie (LeBron + Boogie) is a music player UI prototype showcasing modern React Native development with Lakers team colors and basketball culture aesthetics.

## ✨ Features

### 🏠 Home Screen
- **Recently Played** - Quick access to your recent listening history
- **Made For You** - Personalized playlists (Discover Weekly, Release Radar, Daily Mixes)
- **Your Playlists** - Custom curated collections
- Purple-to-black gradient background (Lakers colors)

### 🔍 Search
- Search bar for finding music
- Category grid navigation (Artists, Albums, Playlists, Genres)
- Top Songs showcase
- Interactive cards with press effects

### 📚 Browse Categories
- **Artists** - Browse by music artists
- **Albums** - Explore album collections
- **Playlists** - Curated music selections
- **Genres** - Filter by music genre

### 🎨 Design Highlights
- **Lakers Color Scheme**:
  - Purple (`#552583`) - Primary color
  - Gold (`#FDB927`) - Accent/active state
  - Black gradient backgrounds
- Smooth gradients and modern UI
- Bottom navigation with icons
- Responsive grid layouts

## 🛠️ Tech Stack

- **React Native** - Cross-platform mobile development
- **Expo Router** - File-based routing with navigation
- **TypeScript** - Type-safe development
- **Expo Linear Gradient** - Beautiful gradient backgrounds
- **FontAwesome Icons** - Navigation and UI icons
- **React Native Gesture Handler** - Smooth interactions
- **React Native Reanimated** - Performant animations

## 📱 Screenshots

> **Note:** Screenshots coming soon! The app features:
> - Home screen with Lakers purple/gold gradient
> - Horizontally scrollable playlist sections
> - Search interface with category grid
> - Bottom navigation bar with Home and Search icons

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Expo Go app on your phone ([iOS](https://apps.apple.com/app/expo-go/id982107779) | [Android](https://play.google.com/store/apps/details?id=host.exp.exponent))
- OR iOS Simulator (Mac) / Android Emulator

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/luciapau-30/expo_lebron.git
   cd expo_lebron/Crabby-main
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npx expo start
   ```

4. **Run on your device**
   - **Phone**: Scan the QR code with Expo Go
   - **iOS Simulator**: Press `i` in the terminal
   - **Android Emulator**: Press `a` in the terminal

## 📁 Project Structure

```
Crabby-main/
├── app/                    # App screens (file-based routing)
│   ├── index.tsx          # Entry point
│   ├── home.jsx           # Home screen with playlists
│   ├── SearchPage.jsx     # Search interface
│   ├── artists.jsx        # Artists browse screen
│   ├── albums.jsx         # Albums browse screen
│   ├── playlists.jsx      # Playlists screen
│   ├── genres.jsx         # Genres screen
│   ├── navbar.jsx         # Bottom navigation component
│   └── _layout.tsx        # Root layout
├── assets/                 # Images, fonts, icons
├── components/             # Reusable components
├── app.json               # Expo configuration
└── package.json           # Dependencies
```

## 🎯 Key Learning Highlights

This project demonstrates proficiency in:

- **Modern React Native Development** - Functional components, hooks, state management
- **Expo Router** - File-based routing and navigation patterns
- **UI/UX Design** - Creating visually appealing interfaces with custom branding
- **TypeScript Integration** - Type-safe mobile development
- **Cross-platform Development** - Building apps that run on iOS and Android
- **Component Architecture** - Modular, reusable component design

## 🏀 Why "LeBoogie"?

The name combines:
- **LeBron** James - Lakers legend and basketball icon
- **Boogie** - Slang for music/dancing

The app brings together Lakers fandom and music culture in a fun, modern mobile experience.

## 🚀 Future Enhancements

- [ ] Connect to real music API (Spotify Web API)
- [ ] Add music playback functionality
- [ ] User authentication and profiles
- [ ] Create custom playlists
- [ ] Like/save favorite songs
- [ ] Social sharing features
- [ ] More Lakers-themed Easter eggs

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Lakers Purple | `#552583` | Primary background, navbar |
| Lakers Gold | `#FDB927` | Active states, highlights |
| Dark Purple | `#301934` | Gradient, accents |
| White | `#FFFFFF` | Text, icons |

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Inspired by Spotify's UI/UX design
- Lakers color scheme from official team branding
- Built with React Native and Expo ecosystem
- Icons by FontAwesome

---

**Built with 💜💛 for Lakers fans and music lovers**

*Go Lakers!* 🏀
