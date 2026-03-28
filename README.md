# 🏙️ Dynamic Glassmorphism Calendar

A high-performance, responsive calendar and real-time clock web application. This project was built to practice modern frontend workflows, including automated builds, code minification, and continuous deployment.

## 🚀 Live Demo
[View the Live Project on Netlify](https://emerald-calendar.netlify.app/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/e5e3937f-490d-4162-8f48-71f063097b9b/deploy-status)](https://app.netlify.com/projects/emerald-calendar/deploys)

## ✨ Key Features
- **Real-time Digital Clock:** Updates every second with a smooth reveal animation.
- **Dynamic Date Tracking:** Automatically pulls the current date, day, and month using JavaScript's `Date` object.
- **Glassmorphism UI:** A modern design aesthetic using CSS back-drop filters and glass transparency.
- **Optimized Reveal:** A custom "Stage Manager" script handles the transition from a loading spinner to the main content once all assets are ready.

## 🛠️ Technical Workflow (Production Ready)
This project moves beyond simple static HTML/CSS by implementing a professional build pipeline:

- **Bundler:** [Vite](https://vitejs.dev/) – Used for Fast Refresh during development and optimized bundling for production.
- **Minification:** [Terser](https://terser.org/) – Implemented custom minification rules to mangle variable names and strip `console.log` statements for a smaller, faster JS footprint.
- **Asset Management:** Leveraged Vite's content hashing to ensure automatic cache-busting on every update.
- **Deployment:** Continuous Integration/Deployment (CI/CD) via GitHub and Netlify.

## 📦 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/my-calendar-app.git](https://github.com/your-username/my-calendar-app.git)