# 🚀 Stulytics: Advanced AI-Powered Student Analytics Dashboard

**Stulytics** is a comprehensive, highly interactive, and visually stunning student analytics platform built with **React** and **Vite**. Designed to transform the way students visualize their academic journey, it packs 14 comprehensive analytics modules, an advanced 8-theme engine, and stunning 3D animations into a highly gamified and interactive experience.

Combining gamification, robust data visualization, an advanced UI engine, and built-in AI study recommendations, Stulytics represents the future of specialized learning management interfaces.

---

## ✨ Comprehensive Feature Breakdown

### 1. 🖥️ Core Dashboard & Analytics (14 Specialized Modules)
The application spans across 14 deeply integrated pages, each serving a unique function in the student's academic journey:
- **Overview Dashboard:** A high-level view of current GPA, recent achievements, upcoming deadlines, and study streaks.
- **Attendance Tracking:** Features GitHub-style study-hour heatmaps, monthly bar charts, and attendance vs. performance correlation engines.
- **Grades & Marks:** Subject-wise radar charts, chapter-level mastery breakdown bars, and historical class averages.
- **Smart Analytics:** Explores deep correlations such as "Study Time vs Score" and identifies "Weak Topics" with visual severity gauges.
- **Gamification & Leaderboards:** A global ranking system, XP (Experience Points) tracking, and a dynamic quest/achievement system to enforce consistency.
- **Behavioral & Brain Map:** Visualizes focus patterns, learning styles (Visual vs. Auditory), and circadian rhythm performance.

### 2. 🤖 The Interactive "Study Buddy" (Live AI Character)
Floating in the bottom right corner of the application is a fully animated, CSS-driven robot companion. 
- **Contextual Awareness:** The character exhibits different moods (idle, happy, thinking) and features a dynamic speech bubble.
- **Actionable AI:** Paired with the glowing "What Should I Study Now?" Floating Action Button (FAB). Clicking it triggers an algorithmic check of the student's weakest chapter mastery and nearest upcoming exam date, generating an instant, customized 3-step study plan.

### 3. 🎨 The 8-Theme Advanced Display Engine
The dashboard breaks away from the standard "Light/Dark" binary by offering 8 deeply integrated, meticulously crafted themes. These themes transition smoothly via CSS variables:
1. **Light Mode & Dark Mode** (Clean, classic precision)
2. **Neon Mode** (High-energy purple/cyan glow)
3. **Soft Pastel** (Low-contrast, eye-friendly aesthetics)
4. **Premium** (Black & Gold luxury layout)
5. **Cyberpunk** (High-tech yellow/blue grit)
6. **Deep Ocean** (Immersive aquatic blues)
7. **Enchanted Forest** (Earthy, vibrant greens)

*Note: The theme changes don't just affect flat colors—they dynamically alter the hue, mesh gradients, and glow intensities of the physical particle backgrounds!*

### 4. 🌌 Immersive 3D Environments & Backgrounds
- **Premium Auth Flow:** The Login and Signup screens abandon flat backgrounds in favor of a stunning, multi-layered 3D animated CSS grid floor paired with a drifting starfield sky.
- **Dynamic Particle Network:** The main dashboard features a lightweight, HTML5 Canvas-based particle network that hums in the background, automatically syncing its connection line colors with the active theme.

### 5. 🗺️ Smart In-Page "Scrollspy" Navigation
Pages with extensive data (like Attendance, Grades, and Analytics) feature a sleek, sticky horizontal anchor navigation bar. One click smoothly scrolls the window directly to the insight you need, constantly tracking your reading position.

### 6. 🔐 Complete Authentication Flow
- Features fully protected React routing using **React Router v6**.
- Includes functional Login and Signup forms with real-time password strength indicators, visibility toggles, and simulated backend local storage persistence (`AuthContext`).

---

## 🛠️ Technical Stack & Architecture

- **Frontend Core**: [React 18](https://react.dev/) powered by [Vite](https://vitejs.dev/) for lightning-fast HMR and building.
- **Styling Architecture**: Pure, advanced Vanilla CSS. Relies heavily on a centralized Root Variable design system (`index.css` & `ThemeContext.jsx`) for instantaneous theme switching without external UI libraries.
- **Routing**: `react-router-dom` for seamless SPA page transitions.
- **Animations**: [Framer Motion](https://www.framer.com/motion/) is utilized for staggered container loading, layout shifts, route transitions, and interactive micro-animations.
- **Data Visualization**: [Chart.js](https://www.chartjs.org/) & `react-chartjs-2` power the complex radar, bar, line, and doughnut charts across the analytics modules.
- **Icons**: [Lucide React](https://lucide.dev/)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites
Make sure you have Node.js (v16+) installed on your machine.

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/harishs20/student-analytics-dashboard-v2.git
   ```
2. Navigate to the project directory
   ```sh
   cd stulytics
   ```
3. Install the NPM dependencies
   ```sh
   npm install
   ```
4. Start the development server
   ```sh
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173/`

---

## 📂 Project Structure

```text
src/
├── components/          # Reusable UI components
│   ├── AI/              # StudyNow FAB, AIAssistant chat
│   ├── Characters/      # Live floating AI robot
│   ├── Effects/         # 3D Grid, Starfield, Canvas Particles
│   └── Layout/          # Sidebar, TopBar, InPageNav
├── contexts/            # Global state management
│   ├── AuthContext.jsx  # LocalStorage authentication logic
│   └── ThemeContext.jsx # 8-Theme engine provider
├── data/                # Mock datasets (grades, attendance, predictive models)
├── pages/               # Top-level route components (Dashboard, Login, Analytics, etc.)
├── App.jsx              # Main router and shell layout
└── index.css            # Global variables, typography, and utility classes
```

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments & Credits

This project was made possible by leveraging the brilliant work of several open-source communities and design principles. We would like to express our gratitude to:

- **[React](https://react.dev/) & [Vite](https://vitejs.dev/)**: For providing an incredible, blazing-fast foundation for modern web development.
- **[Framer Motion](https://www.framer.com/motion/)**: For the powerful, declarative animation library that brings the UI to life.
- **[Chart.js](https://www.chartjs.org/)**: The elegant, responsive data visualization backbone utilized across all our analytics graphs.
- **[Lucide React](https://lucide.dev/)**: For the beautiful, consistent, and lightweight SVG icon set used throughout the application.
- **[GitHub Calendar/Heatmap](https://github.com/)**: For the conceptual inspiration behind our interactive "Study Hour Heatmap" tracking UI.

---

## 👥 Team Members

This project was collaboratively designed and developed by:

- **Harish** - `24BCE1440`
- **Shailesh K S** - `24BCE1417`
- **Kopathy K** - `24BCE1451`
