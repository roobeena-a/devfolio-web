# DevFolio - Student Personal Portfolio Website

A responsive, single-page student developer portfolio engineered for the **Hackathon Level 2 - Fundamentals of Web Development** under the Tamil Nadu Skill Development Initiative and Oracle sponsorship.

---

## 👩‍💻 Developer Details
- **Student Name:** ROOBEENA A
- **Register Number:** 25132061802522068
- **Student ID:** 20625UCSE233
- **Department:** B.Sc. Computer Science
- **College:** Thiru. A. Govindhasamy Govt Arts College, Tamil Nadu
- **Curriculum:** Fundamentals of Web Development (Oracle / TN Skill)

---

## 🚀 Key Features Implemented

1. **Responsive Glassmorphism Navigation:**
   - Sticky frosted navbar (`backdrop-filter: blur()`).
   - Collapsible mobile drawer hamburger navigation.
2. **Dual-Theme Engine with Persistence:**
   - Smooth Light / Dark mode toggle.
   - Retains state across browser refreshes via `localStorage`.
3. **Hero Stage & Finite State Machine Typewriter:**
   - Continuous role typewriter animation (`Computer Science Undergraduate`, `Full-Stack Developer Enthusiast`, etc.).
   - Interactive developer code persona IDE card (`roobeena.ts`).
4. **Academic Timeline & Competency Metrics:**
   - Connected chronological academic timeline.
   - 4 quantitative milestone metric counters (CGPA 8.84, 250+ DSA problems).
5. **Interactive Skills Matrix:**
   - Categorized skills filterable by pills (*Languages*, *Web*, *Databases*, *Tools*).
   - Dynamic proficiency progress bars.
6. **Dynamic In-Memory Project Filtering:**
   - Project cards injected via JavaScript from an in-memory data store.
   - Filterable pills (*All*, *Full Stack*, *Java / Python*, *Systems*).
   - Deep-dive technical modal dialogs (`ESC` to close).
7. **Downloadable Resume Feature:**
   - Real-time formatted CV generated and downloaded using the JavaScript `Blob` API.
8. **Validated Contact Form:**
   - Strict RFC 5322 email regex verification.
   - Async submit feedback button state and floating 3.5-second toast alerts.

---

## 🛠️ Technology Stack
- **HTML5:** Semantic architecture (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- **CSS3 / Tailwind CSS:** Utility tokens via CDN, custom dark palette tokens, responsive grid/flexbox.
- **JavaScript (ES6+):** Vanilla DOM manipulation, FSM typewriter, event listeners, LocalStorage API.
- **Vector Icons:** Lucide Icons library via CDN.

---

## 📂 Project Structure
```text
DevFolio-Student-Portfolio/
├── index.html          # Main single-page web application
├── README.md           # Documentation, setup guide, and project details
├── .gitignore          # Standard git ignore file
└── LICENSE             # MIT Open Source License
```

---

## ⚡ How to Run Locally

1. Clone or extract this repository:
   ```bash
   git clone https://github.com/<your-username>/DevFolio-Student-Portfolio.git
   ```
2. Open `index.html` directly in any modern browser (Chrome, Edge, Firefox, Safari).
3. No build tools, NodeJS, or external package installations are needed!

---

## 🌐 GitHub Upload Steps

To push this project to your GitHub account:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: DevFolio Hackathon Level 2 Student Portfolio"

# Set default branch
git branch -M main

# Link to your remote GitHub repository
git remote add origin https://github.com/<your-username>/<your-repo-name>.git

# Push to GitHub
git push -u origin main
```

To enable **GitHub Pages** (Live Website):
1. Go to repository **Settings** > **Pages**.
2. Under **Branch**, select `main` and root `/`.
3. Click **Save** — your site will be live within seconds!
