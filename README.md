# MantraOS ✨

<p align="center">
  <img src="https://img.shields.io/badge/version-1.1.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/PWA-installable-brightgreen.svg" alt="PWA Installable">
  <img src="https://img.shields.io/badge/Chrome_AI-integrated-blueviolet.svg" alt="Chrome AI Integrated">
</p>

**MantraOS** is a motivational progressive web application (PWA) supercharged with on-device AI to help you cultivate a positive mindset. Choose from a curated library, create your own powerful mantras, or generate new ones with AI. Get on-the-fly translations, rephrase mantras for more impact, and perfect your writing with grammar correction—all while your data stays private on your device.

Built as a self-contained, **zero-dependency vanilla JavaScript application**, it's fast, private, reliable, and works completely offline.

---

## 🌟 Features at a Glance

| Feature                 | Description                                                                 | Status |
| ----------------------- | --------------------------------------------------------------------------- | :----: |
| **AI Mantra Generation**  | Use on-device AI to generate new, personalized mantras on any topic.        |   ✅    |
| **AI Translation**      | Instantly translate all mantras into multiple languages using local AI.     |   ✅    |
| **AI Rewriting**        | Rephrase any mantra in three different styles for greater impact.           |   ✅    |
| **AI Grammar Check**    | Automatically proofread and correct your custom-written mantras.            |   ✅    |
| **Voice Recording**     | Record your own voice for each mantra for a personalized experience.        |   ✅    |
| **Progress Tracking**     | Visualize consistency with streaks, stats, and an activity calendar.        |   ✅    |
| **Full Customization**  | Choose themes, fonts, dark mode, and enable haptic feedback.              |   ✅    |
| **PWA & Offline-First** | Install on your device and use it anywhere, with or without a connection. |   ✅    |
| **Data Portability**    | Export and import all your data with a single click. No lock-in.          |   ✅    |

---

## 📚 Table of Contents

- [Live Demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Chrome AI Integration](#-chrome-ai-integration)
- [Key Features](#-key-features)
- [How It Works](#-how-it-works)
- [Technology Stack](#️-technology-stack)
- [🚀 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [🗺️ Roadmap](#️-roadmap)
- [File Structure](#-file-structure)
- [License](#-license)

## 🌐 Live Demo

**[🚀 Try MantraOS Now!](https://mantraos.netlify.app)**

✨ **Pro Tip:** Install as PWA for best experience!

## 📸 Screenshots

| Onboarding | Dashboard |
| :---: | :---: |
| ![Onboarding Screen](https://github.com/alljaybly/mantraOS/blob/main/Onboarding.png?raw=true) | ![Dashboard Screen](https://github.com/alljaybly/mantraOS/blob/main/Dashboard.png?raw=true) |
| *A smooth onboarding to personalize your experience.* | *Your daily mantra with voice and AI controls.* |

| Library | Settings |
| :---: | :---: |
| ![Library Screen](https://github.com/alljaybly/mantraOS/blob/main/Library.png?raw=true) | ![Settings Screen](https://github.com/alljaybly/mantraOS/blob/main/Settings.png?raw=true) |
| *Manage your collection, now with AI generation.* | *Enable AI features and choose your language.* |

## 🤖 Chrome AI Integration

MantraOS is architected to leverage Chrome's on-device AI APIs for enhanced personalization. The app automatically detects AI availability and provides clear instructions for enabling these privacy-preserving features.

**Current Status:** AI APIs in early preview - detection system active
**Future Ready:** Full integration prepared for API availability

## ✨ Key Features

### 🤖 On-Device AI Features (Powered by Chrome)
- **AI Mantra Generation:** Feeling uninspired? Enter a topic like "confidence" or "calmness" and let the on-device AI generate a list of new, relevant mantras for you to add to your collection.
- **Multilingual Translation:** Automatically detects your browser's language and can translate your entire mantra library on the fly. All translations happen locally.
- **Mantra Personalization (Rewriting):** Tap a button to have the AI rephrase any mantra in three different ways, helping you find the words that resonate most deeply.
- **Grammar Correction:** As you write your own custom mantras, a built-in grammar check suggests improvements to ensure your affirmations are clear and powerful.

### 🧘‍♀️ Main Dashboard
- **Daily Mantra View:** A clean, focused interface to view your daily mantra.
- **Intuitive Navigation:** Swipe left or right to effortlessly navigate between your selected mantras.
- **At-a-Glance Stats:** Key metrics like Total Views, Current Streak, and Views Today are displayed prominently.

### 🎤 Voice Personalization
- **Record Your Voice:** Bring your mantras to life by recording your own voice reading them aloud (up to 30 seconds per mantra).
- **Full Playback Control:** Play, pause, stop, re-record, and delete your voice memos with an intuitive interface.

### 🎉 Motivational Feedback
- **Celebrations:** Experience a burst of confetti and satisfying sound effects upon completing your daily goal or hitting a 7-day streak.
- **Haptic Feedback:** Feel subtle vibrations on key interactions for a more tactile experience.

### 📚 Library
- **Discover & Manage:** Explore a rich library of pre-written mantras, manage your own, and sort them by priority or date.
- **Integrated AI & Voice:** All management features, including AI rewrite and voice recording, are available directly in the library.

### ⚙️ Settings & Personalization
- **Theme & Font Customization:** Choose from multiple beautiful color gradients and two distinct font styles.
- **AI Controls:** A dedicated section to enable or disable AI features and select your preferred language.
- **Data Management:** Securely export all your data to a JSON file for backup and import it on any device.

## 🤔 How It Works

MantraOS is a **single, self-contained `index.html` file**.

- **State Management:** A global JavaScript `state` object holds all user data.
- **Local Persistence:** The `localStorage` API is used to save the entire application state. This ensures that all your data is stored securely on your device and is available offline.
- **On-Device AI:** The application leverages Chrome's Built-in AI APIs (`window.ai`). All AI processing happens directly in the browser, meaning your data is never sent to a server. This ensures privacy, speed, and full offline functionality for core features.
- **Dynamic Rendering:** The UI is dynamically rendered using vanilla JavaScript functions that generate HTML strings and mount them to the DOM.

## 🛠️ Technology Stack

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3
- **Web APIs:**
  - **Chrome's Built-in AI API** (`ai.createTextSession`, `ai.translator.create`, `ai.rewriter.create`, `ai.proofreader.create`)
  - `localStorage`, `MediaRecorder API`, `Web Audio API`, `Vibration API`
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- **Icons:** [Lucide Icons](https://lucide.dev/) embedded as SVG functions.
- **Deployment:** Can be hosted on any static web hosting service.

## 🚀 Getting Started

Since this is a vanilla web application, there is no complex build process.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/mantra-os.git
    ```

2.  **Navigate to the directory:**
    ```bash
    cd mantra-os
    ```

3.  **Run locally:**
    You must serve the files from a local web server for the AI and PWA features to work correctly.

    #### Using VS Code
    The easiest way is the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). Right-click `index.html` and select "Open with Live Server".

    #### Using Node.js
    ```bash
    # Install serve globally (one-time)
    npm install -g serve
    # Run from the project directory
    serve .
    ```

    After starting the server, open the provided URL (e.g., `http://localhost:3000`) in your browser.

## 🤝 Contributing

Contributions are greatly appreciated! Please fork the repo and create a pull request.

1.  **Fork the Project**
2.  **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the Branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

## 🗺️ Roadmap

- [ ] **Custom Categories:** Allow users to create and manage their own mantra categories.
- [ ] **Journaling:** A space to write down thoughts and reflections related to your daily mantra.
- [ ] **More Themes & Sounds:** Expand the library of customization options.
- [ ] **Data Sync:** Optional, privacy-focused cloud sync to keep data consistent across devices.

## 🗂️ File Structure

The project has been intentionally consolidated to simplify its architecture:

-   `index.html`: The core of the application. Contains all HTML, CSS (via Tailwind config and style blocks), and JavaScript logic.
-   `README.md`: This file.
-   `manifest.json`: The Progressive Web App (PWA) manifest file.
-   `icon-192.svg` / `icon-512.svg`: App icons used for the PWA.
-   `metadata.json`: Project metadata.
-   `index.tsx`, `service-worker.js`, etc.: These files are intentionally blank or unused. The project was refactored into a single HTML file to resolve critical errors and simplify the stack.

## 📜 License

This project is distributed under the MIT License. See [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT).
