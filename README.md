# MantraOS ✨

**MantraOS** is a motivational PWA supercharged with on-device AI, submitted to the Google Chrome Built-in AI Challenge 2025. It's designed to excel in the **"Best Multimodal AI Application"** category by transforming spoken intentions into powerful, personalized mantras.

Speak your goals, and the app's privacy-preserving, on-device AI crafts affirmations for you. This core multimodal feature is complemented by AI-powered translation, rephrasing, and grammar correction, all running offline in a fast, zero-dependency vanilla JavaScript application.

---

### 🚀 Setup for Hackathon Judges

To experience the full on-device AI capabilities, please follow these steps:

1.  **Browser:** Use **Chrome Canary** and enroll in the [Early Preview Program (EPP)](https://developer.chrome.com/docs/ai/built-in/internal-features).
2.  **Flags:** Enable `chrome://flags/#prompt-api-for-gemini-nano` and `chrome://flags/#optimization-guide-on-device-model`.
3.  **Hardware:** Ensure your device has **8GB+ of RAM**.
4.  **Demo Mode:** If on-device AI is unavailable, a toast notification will appear. You can **enable "Demo Mode" in Settings** to simulate all AI features, including multimodal audio input.

---

### 🌟 Key Features

-   **🏆 Multimodal Mantra Generation**: The flagship feature. Simply **speak a topic** like "confidence" or "calmness," and the on-device AI will transcribe your voice and generate a list of relevant mantras.
-   **Voice of Power Achievement**: Unlock a special achievement for using the new voice generation feature.
-   **Advanced AI Toolkit**: Enhance your mantras with on-the-fly translation, intelligent rephrasing, and instant grammar correction.
-   **Full PWA & Offline-First**: Installable on any device and works completely offline, with all data stored locally.
-   **Voice & UI Customization**: Record your own voice for mantras and personalize the app with multiple themes, fonts, and dark mode.
-   **Data Portability**: Export and import all your data with a single click.

### 🛠️ Technology Stack

-   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3
-   **Web APIs:**
    -   **Chrome's Built-in AI API** (`window.ai.assistant.prompt`, `createTextSession`, `translator`, `rewriter`, `proofreader`)
    -   `localStorage`, `MediaRecorder API`, `Web Audio API`
-   **Styling:** Tailwind CSS (via CDN)
-   **Icons:** Lucide Icons (embedded as SVG functions)
-   **Deployment:** Any static web hosting service.