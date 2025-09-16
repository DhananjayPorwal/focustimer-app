# FocusTimer

> A simple productivity timer app built with React Native and Expo.

## Overview

FocusTimer helps you stay productive by allowing you to set a focus subject, start a countdown timer, and track your focus history. The app is inspired by the Pomodoro technique and is designed to be minimal, beautiful, and easy to use.

## Features

- Set a custom focus subject for each session
- Start, pause, and reset a countdown timer
- Choose timer durations (10, 15, or 20 minutes)
- Keep your device awake during focus sessions
- View a history of your completed focus sessions
- Simple, clean, and responsive UI

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DhananjayPorwal/focustimer-app.git
   cd focustimer-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Run on your device:
   - Use the Expo Go app to scan the QR code, or
   - Run on an emulator with `npm run android` or `npm run ios`

## Project Structure

```
FocusTimer/
├── App.js
├── assets/
├── src/
│   ├── components/
│   │   ├── Countdown.js
│   │   └── RoundedButtons.js
│   ├── features/
│   │   ├── focus.js
│   │   ├── FocusHistory.js
│   │   ├── Timer.js
│   │   └── Timing.js
│   └── utils/
│       ├── colors.js
│       └── sizes.js
├── package.json
└── README.md
```

## Main Components

- **Focus**: Input your focus subject for the session.
- **Timer**: Countdown timer with start/pause and duration selection.
- **FocusHistory**: View your previous focus sessions.
- **Countdown**: Animated countdown display.
- **RoundedButton**: Custom button component for actions.

## Customization

- Change timer durations in `src/features/Timing.js`.
- Adjust colors and spacing in `src/utils/colors.js` and `src/utils/sizes.js`.
