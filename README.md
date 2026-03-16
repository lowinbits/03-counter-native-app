# 03 - Counter App

A simple counter application built with **React Native** and **Expo**, developed as part of a React Native learning course.

## What does this app do?

- Displays a counter on screen
- Floating **+1** button to increment the counter
- **Long press** the button to reset the counter to 0

## Concepts practiced

- Functional components with React
- `useState` hook for state management
- `Pressable` component with `onPress` / `onLongPress` events
- Styling with `StyleSheet.create`
- Absolute positioning (floating button)
- Shadows on Android (`elevation`) and iOS (`shadow*`)

## Requirements

- [Node.js](https://nodejs.org/) 18+
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Expo Go installed on your physical device, or a configured Android/iOS emulator

## Installation & Usage

```bash
# Clone the repository
git clone <repo-url>
cd 03-counter-app

# Install dependencies
npm install

# Start the development server
npx expo start
```

Then scan the QR code with **Expo Go** (Android) or the camera app (iOS), or press:

- `a` to open on Android emulator
- `i` to open on iOS simulator
- `w` to open in the web browser

## Stack

| Technology | Version |
|---|---|
| Expo SDK | ~54.0.0 |
| React Native | 0.81.5 |
| React | 19.1.0 |
| TypeScript | ~5.9.2 |

## Project Structure

```
03-counter-app/
├── App.tsx          # Root component with all logic and UI
├── index.ts         # Entry point (registerRootComponent)
├── assets/          # Icons and splash screen
└── app.json         # Expo configuration
```

---

> Practice project — React Native Course
