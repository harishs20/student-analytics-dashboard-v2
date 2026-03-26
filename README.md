# 🚀 Stulytics: Ultra Student Analytics Dashboard

Stulytics is a premium, AI-powered student analytics platform built with **React** and **Vite**. Designed to transform the way students visualize their academic journey, it packs 14 comprehensive analytics modules, an advanced 8-theme engine, and stunning 3D animations into a highly gamified and interactive experience.

## ✨ Core Features

### 🎨 8-Theme Advanced Display Engine
Experience the dashboard exactly how you want it. The platform features a dynamic CSS-variable theme engine that seamlessly transitions not just colors, but also the physical particle backgrounds:
- **Light & Dark Mode** (Clean, classic precision)
- **Neon Mode** (High-energy purple/cyan glow)
- **Soft Pastel** (Low-contrast, eye-friendly aesthetics)
- **Premium** (Black & Gold luxury)
- **Cyberpunk** (High-tech yellow/blue grit)
- **Deep Ocean** (Immersive aquatic blues)
- **Enchanted Forest** (Earthy, vibrant greens)

### 🤖 Floating AI "Study Buddy"
A completely interactive, animated companion lives in the bottom right corner of your screen. The AI Study Buddy reacts to your presence and provides one-click instant recommendations on "What to Study Next" based on your weakest subjects and upcoming exams.

### 🌌 Immersive & Dynamic 3D Backgrounds
- **Auth Flow**: The Login and Signup pages feature a stunning, multi-layered 3D animated CSS grid floor paired with a drifting starfield sky.
- **Dashboard**: A lightweight, canvas-based particle network hums in the background, automatically changing its connection hues to match your active theme.

### 🗺️ Smart In-Page Navigation
Pages with extensive data (like Attendance, Grades, and Analytics) feature a sleek, sticky horizontal anchor navigation bar. One click smoothly scrolls you directly to the insight you need.

### 📊 Comprehensive Modules
- **Overview Dashboard**: High-level metrics, XP tracking, and quick-glance performance trends.
- **Attendance & Heatmaps**: GitHub-style study-hour heatmaps and attendance-vs-performance correlations.
- **Grades & Analytics**: Chapter-level mastery tracking, subject comparison radars, and historical consistency scores.
- **Gamification & Social**: Global leaderboards, leveling systems, and XP streaks to keep you motivated.

## 🛠️ Tech Stack

- **Framework**: [React 18](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Styling**: Pure vanilla CSS using a robust Root Variable design system
- **Routing**: React Router DOM (v6)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Charting**: [Chart.js](https://www.chartjs.org/) & `react-chartjs-2`
- **Icons**: [Lucide React](https://lucide.dev/)

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites
Make sure you have Node.js installed on your machine.

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your-username/stulytics-dashboard.git
   ```
2. Navigate to the project directory
   ```sh
   cd stulytics
   ```
3. Install the dependencies
   ```sh
   npm install
   ```
4. Start the development server
   ```sh
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173/`

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

## 🔐 Authentication
Stulytics currently utilizes an advanced mock authentication flow that connects to `localStorage`. Registration captures your user name and credentials, persisting them securely locally. Protected routes ensure guests are redirected to the immersive login portal.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
