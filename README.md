# 🕉️ Samskrita Swayam Shikshaka (ಸಂಸ್ಕೃತ-ಸ್ವಯಂ-ಶಿಕ್ಷಕಃ)
> **A Bilingual Interactive Sanskrit Learning Web Application by Team Trayee.**

![Project Status](https://img.shields.io/badge/Status-Active_Development-success)
![Language](https://img.shields.io/badge/Language-Kannada%20%7C%20English%20%7C%20Sanskrit-orange)
![Tech Stack](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-blue)

## 📌 About the Project
Samskrita Swayam Shikshaka is a gamified, self-paced learning platform designed to teach conversational and grammatical Sanskrit in just 10 minutes a day. The project specifically focuses on traditional Sanskrit grammar (Paninian rules) simplified into "Magic Sutras" for modern learners. 

The entire application is completely bilingual, allowing users to seamlessly switch between **Kannada** and **English** instruction mediums without reloading the page.

## ✨ Key Features
* **Bilingual Interface:** Real-time toggle between Kannada and English using `localStorage`. 
* **Interactive Level Map:** A visually engaging "Candy Crush" style level progression map with animated SVG paths.
* **Gamified Learning:** * Drag-and-Drop Sentence Builders (ವಾಕ್ಯ ನಿರ್ಮಾಣ).
    * Click-to-reveal Word Puzzles (ಶಬ್ದ ಶೋಧನಮ್).
    * Match the Following logic tests.
    * Odd One Out exercises.
* **Shabda Shevadhi (ಶಬ್ದ ಶೇವಧಿಃ):** A unique, interactive circular modal that acts as a digital dictionary, visualizing complete word declensions (Vibhaktis) dynamically. Unlocks progressively as levels advance.
* **Visual Storytelling:** Zig-zag layout integrating narrative stanzas, translations, and emoji/image art to build reading comprehension.
* **Progressive Assessment:** Comprehensive multi-part exams at key milestones to test retention before unlocking new concepts.

## 🗂️ Project Structure
The project is built using pure Vanilla web technologies. No servers, build steps, or frameworks are required.

```text
📁 Samskrita-Swayam-Shikshaka/
│
├── index.html        # Main landing page & interactive level map
├── level1.html       # Intro to 1st & 2nd Person (अहं, त्वं)
├── level7.html       # Dvitiya Vibhakti (Object / Karma Karaka)
├── level8.html       # Story Time: Grudhrasya Karuna (Reading Comprehension)
├── level9.html       # Saptami Vibhakti Introduction (Location / Adhikarana)
├── level10.html      # Saptami Vibhakti Complete Singular & Magic Sutras
├── level11.html      # Mega Exam: Saptami Vibhakti Multi-format Quiz
└── README.md         # Project documentation
🛠️ Technical Details
HTML5: Semantic markup structured for readability and accessibility.

CSS3: * Custom CSS variables (:root) for consistent theming (Parchment, Maroon, Gold).

Flexbox and CSS Grid for fully responsive layouts across mobile and desktop.

Keyframe animations for visual feedback (shakes for wrong answers, bouncing arrows, floating icons).

Vanilla JavaScript:

DOM manipulation for quizzes and drag-and-drop games.

State management using localStorage (tracking the user's language preference trayeeLang).

Fisher-Yates shuffle algorithm to randomize quiz options and word banks on every load.

🚀 How to Run
Clone or download the repository to your local machine.

Ensure all HTML files are in the same folder.

Simply double-click index.html to open it in any modern web browser (Chrome, Safari, Firefox, Safari).

No internet connection is strictly required for core functionality, though an active connection is needed to load external Google Fonts (Inknut Antiqua, Laila, Tiro Devanagari Sanskrit) and FontAwesome icons.

🎯 Educational Pedagogy
The app follows a strict pedagogical flow:

Rule Introduction: Presenting the concept clearly with visual highlights.

Magic Sutras: Condensing complex grammatical rules into easy-to-remember phonetic formulas (e.g., e, ām, au, ām, au, ām, ari, i for 7th Case).

Application (Stories/Subhashitas): Contextualizing the grammar in classic literature, Chanakya Neeti, or moral stories.

Self-Evaluation: Allowing learners to rate their own comprehension percentage before revealing translations.

Gamified Testing: Immediate application through drag-and-drop and quizzes.

Created with dedication by Team Trayee. "समानशीलव्यसनेषु सख्यम्"
