# MantraOS ✨

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/PWA-installable-brightgreen.svg" alt="PWA Installable">
  <img src="https://img.shields.io/badge/Offline-capable-green.svg" alt="Offline Capable">
</p>

**MantraOS** is a motivational progressive web application (PWA) designed to help you cultivate a positive mindset. Choose from a curated library, create your own powerful mantras, track your progress, and receive smart notifications to stay inspired throughout your day.

Built as a self-contained, **zero-dependency vanilla JavaScript application**, it's fast, private, reliable, and works completely offline.

---

## 🌟 Features at a Glance

| Feature                 | Description                                                                 | Status |
| ----------------------- | --------------------------------------------------------------------------- | :----: |
| **Personalized Mantras**  | Select from a curated library or create your own custom affirmations.       |   ✅    |
| **Progress Tracking**     | Visualize your consistency with streaks, stats, and an activity calendar. |   ✅    |
| **Achievements**        | Unlock badges for reaching milestones on your journey.                      |   ✅    |
| **Full Customization**  | Choose themes, fonts, and enable a sleek dark mode.                         |   ✅    |
| **Smart Notifications** | Set reminders for mantras and daily affirmations.                           |   ✅    |
| **PWA & Offline-First** | Install on your device and use it anywhere, with or without a connection. |   ✅    |
| **Data Portability**    | Export and import all your data with a single click. No lock-in.          |   ✅    |

---

## 📚 Table of Contents

- [Live Demo](#live-demo)
- [Screenshots](#screenshots)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Technology Stack](#technology-stack)
- [🚀 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [🗺️ Roadmap](#️-roadmap)
- [File Structure](#file-structure)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Feedback & Support](#feedback--support)


## 🌐 Live Demo

Check out the live version of MantraOS here: **[Live Demo Link Coming Soon]**

## 📸 Screenshots

*(Replace the placeholder URLs with actual screenshots of your application)*

| Onboarding | Dashboard |
| :---: | :---: |
| ![Onboarding Screen](https://via.placeholder.com/400x800.png/667eea/FFFFFF?text=Onboarding) | ![Dashboard Screen](https://via.placeholder.com/400x800.png/667eea/FFFFFF?text=Dashboard) |
| *Seamless setup to personalize your experience.* | *Your daily mantra with quick-glance stats.* |

| Library | Progress |
| :---: | :---: |
| ![Library Screen](https://via.placeholder.com/400x800.png/667eea/FFFFFF?text=Library) | ![Progress Screen](https://via.placeholder.com/400x800.png/667eea/FFFFFF?text=Progress) |
| *Discover new mantras and manage your collection.* | *Track your consistency and unlock achievements.* |

| Settings |
| :---: |
| ![Settings Screen](https://via.placeholder.com/400x800.png/667eea/FFFFFF?text=Settings) |
| *Customize themes, fonts, and notifications.* |


## ✨ Key Features

### onboarding-experience
- **Guided Setup:** A seamless, multi-step onboarding process to personalize the app from the start.
- **Personalized Mantras:** Users select 3 to 5 core mantras from curated categories that resonate with their goals.
- **Custom Creation:** Ability to create and add your own personal mantras during the setup process.

### 🧘‍♀️ Main Dashboard
- **Daily Mantra View:** A clean, focused interface to view your daily mantra.
- **Intuitive Navigation:** Swipe left or right to effortlessly navigate between your selected mantras.
- **At-a-Glance Stats:** Key metrics like Total Views, Current Streak, and Views Today are displayed prominently.
- **Daily Affirmation:** Displays a user-added affirmation for an extra boost of positivity.

### 📚 Library
- **Discover Mantras:** Explore a rich library of pre-written mantras organized by categories like Money, Health, Relationships, Career, and Confidence.
- **Search & Filter:** Easily find mantras within categories using a search bar.
- **Manage Your Mantras:** View all your added mantras, remove ones that no longer serve you, assign a priority level (Low, Medium, High), and sort them to your liking.
- **Manage Your Affirmations:** A dedicated section to add, view, and remove your personal daily affirmations.

### 📊 Progress Tracking
- **Detailed Statistics:** A dedicated progress screen shows your Total Views, Current Streak, and your all-time Longest Streak.
- **Top Mantra:** See which mantra you engage with the most.
- **Achievements:** Unlock badges for milestones like viewing your first mantra, maintaining a 7-day streak, or creating a custom mantra.
- **Interactive Calendar:** A visual calendar highlights the days you were active, providing a clear picture of your consistency.

### ⚙️ Settings & Personalization
- **Theme Customization:** Choose from multiple beautiful color gradients to match your mood.
- **Font Selection:** Switch between a modern sans-serif font (Poppins) and an elegant serif font (Playfair Display).
- **Dark Mode:** A sleek dark mode for comfortable viewing in low-light conditions.
- **Smart Notifications:** Configure reminders for your mantras (morning, afternoon, evening) and a separate reminder for your daily affirmation.
- **PWA Installation:** Install MantraOS to your home screen for a fast, native-app-like experience.
- **Data Management:** Securely export all your data to a JSON file for backup and import it on any device.
- **Application Reset:** A simple option to reset all application data and start fresh.

## 🤔 How It Works

MantraOS is designed for simplicity and performance. The entire application is a **single, self-contained `index.html` file**.

- **State Management:** A global JavaScript `state` object holds all user data, including mantras, settings, and progress.
- **Local Persistence:** The `localStorage` API is used to save the entire application state. This ensures that all your data is stored securely on your device and is available even when you're offline.
- **Client-Side Logic:** There is no backend server. All logic, from rendering views to tracking progress, is handled directly in the user's browser, making it fast and private.
- **Dynamic Rendering:** The UI is dynamically rendered using vanilla JavaScript functions that generate HTML strings and mount them to the DOM. This approach avoids the need for heavy frameworks.

## 🛠️ Technology Stack

- **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN) for rapid, utility-first styling.
- **Icons:** [Lucide Icons](https://lucide.dev/) embedded as SVG functions.
- **Deployment:** Can be hosted on any static web hosting service (like Vercel, Netlify, or GitHub Pages).

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
    You can open the `index.html` file directly in your browser. However, for the best experience and to enable Progressive Web App (PWA) features like the "Install App" button, you must serve the files from a local web server. This is because modern browser security policies restrict PWA features to `http` or `https` protocols, not the `file://` protocol used when opening files directly.

    Here are a few ways to start a local server:

    #### Using Node.js
    If you have Node.js installed, you can use a simple package like `serve`.

    1.  **Install `serve` globally (one-time setup):**
        ```bash
        npm install -g serve
        ```
    2.  **Run the server from the project directory:**
        ```bash
        serve .
        ```
    
    An alternative to `serve` is `live-server`, which automatically reloads the page when you make changes.
    1.  **Install `live-server` globally:** `npm install -g live-server`
    2.  **Run it:** `live-server`

    #### Using Python
    If you have Python installed, you can use its built-in web server.

    -   For Python 3:
        ```bash
        python -m http.server
        ```
    -   For Python 2:
        ```bash
        python -m SimpleHTTPServer
        ```

    #### Using VS Code
    If you use Visual Studio Code, a popular and easy-to-use option is the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). Once installed, you can right-click the `index.html` file and select "Open with Live Server".

    After starting the server with any of these methods, open the provided URL (e.g., `http://localhost:3000`, `http://localhost:8000`) in your browser to use the application.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1.  **Fork the Project**
2.  **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the Branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

## 🗺️ Roadmap

Here are some of the features planned for the future:

- [ ] **Custom Categories:** Allow users to create and manage their own mantra categories.
- [ ] **Text-to-Speech:** An option to listen to your mantras.
- [ ] **More Achievements:** Add new badges and milestones to keep users engaged.
- [ ] **Journaling:** A space to write down thoughts and reflections related to your daily mantra.
- [ ] **Data Sync:** Optional cloud sync to keep data consistent across devices (privacy-focused).

See the [open issues](https://github.com/your-username/mantra-os/issues) for a full list of proposed features (and known issues).

## 🗂️ File Structure

The project has been intentionally consolidated to simplify its architecture:

-   `index.html`: The core of the application. Contains all HTML, CSS (via Tailwind config and style blocks), and JavaScript logic.
-   `README.md`: This file.
-   `manifest.json`: The Progressive Web App (PWA) manifest file.
-   `icon-192.svg` / `icon-512.svg`: App icons used for the PWA.
-   `metadata.json`: Project metadata.
-   `index.tsx`, `service-worker.js`, etc.: These files are intentionally blank or unused. The project was refactored into a single HTML file to resolve critical errors and simplify the stack.

## 📜 License

This project is distributed under the MIT License. See the license file for more information, or visit [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT).

## 🙏 Acknowledgments

-   **[Tailwind CSS](https://tailwindcss.com/)**: For the utility-first CSS framework that made styling fast and consistent.
-   **[Lucide Icons](https://lucide.dev/)**: For the beautiful and clean icon set.
-   **[Google Fonts](https://fonts.google.com/)**: For providing the Poppins and Playfair Display fonts.

## 💬 Feedback & Support

Have a bug or a feature request? Please [open a new issue](https://github.com/your-username/mantra-os/issues/new). Your feedback is invaluable!
