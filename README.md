# 🔢 Guess The Number

An interactive single-page web page built with **HTML, CSS (Bootstrap 5), and Vanilla JavaScript**. Designed to deliver a polished &  interactive user experience with dynamic visual feedback, web audio effects, and state persistence.

🔗 [Live Demo](https://emoytech.github.io/number-guesser/)

---

## 🎥 Demonstration

> *Screen Recording Demonstrating all core interactions and features.*

[screen recording](https://github.com/Emoytech/number-guesser/assets/demonstration.webm)

---

## ✨ Features & Interactions

1. **Interactive Guessing Engine (Core Interaction):**
   * Real-time attempt counter and conditional feedback (Too High / Too Low / Spot On!).
   * Dynamic CSS animation (`@keyframes shake`) on incorrect guesses.
   * Web Audio API synthesized sound cues (pitch variations for wins/misses).

2. **Dynamic Hint (Secondary Interaction):**
   * "Need Help" button analyzes the secret number and reveals whether it is **EVEN** or **ODD** to assist the player.

3. **Dark / Light Theme Toggle (Visual Interaction):**
   * Custom theme switcher providing seamless dark mode styling across Bootstrap cards and typography.

4. **Local Storage Integration:**
   * Automatically persists and updates your personal best record (lowest attempts) across browser sessions.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **UI Framework:** [Bootstrap 5.3](https://getbootstrap.com/) (via CDN)
* **Audio:** Native Web Audio API
* **Deployment:** GitHub Pages

---

## 🚀 Local Setup Instructions

No build steps, node modules, or bundlers required!

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emoytech/number-guesser.git](https://github.com/emoytech/number-guesser.git)
