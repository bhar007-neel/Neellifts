<!-- Banner -->
<p align="center">
  <img alt="Neelnormous" src="https://img.shields.io/badge/🏋️‍♂️%20Neelnormous-AI%20Workout%20Generator-1e293b?style=for-the-badge&logo=thunderbird&logoColor=white">
</p>

<h1 align="center">🏋️‍♂️ Neelnormous – <em> Workout Generator</em></h1>

<p align="center">
  <a href="https://neellifts.netlify.app/">
    <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-Click%20to%20Open-10b981?style=for-the-badge">
  </a>
  <img alt="React" src="https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=061c2b">
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-3+-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=0c2a3a">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ES6+-f5d04e?style=for-the-badge&logo=javascript&logoColor=2b2b2b">
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-8b5cf6?style=for-the-badge">
</p>

<p align="center">
  <b>Neelnormous</b> is an interactive, browser-based workout generator that creates <b>custom training plans</b> based on your goals, target muscle groups, and preferred split.<br/>
  Built with <b>React + Tailwind</b>, it uses a curated exercise knowledge base to ensure variety, progression, and personalization.
</p>

<br/>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-demo">Demo</a> •
  <a href="#-tech-stack">Tech</a> •
  <a href="#-project-structure">Structure</a> •
  <a href="#-quickstart">Quickstart</a> •
  <a href="#-how-it-works">How it works</a> •
  <a href="#-roadmap">Roadmap</a>
</p>

---

## 🚀 Features

- **Custom Workout Generation** — Pick your split (“poison”), muscles, and goal to instantly get a tailored plan.  
- **Dynamic Exercise Cards** — Clear muscle targets, reps, rest, and tempo for each move.  
- **Progress Tracking** — Tap **Sets completed** to track sets on the fly.  
- **Multiple Training Styles** — *Bro split, upper/lower, individual muscles,* and more.  
- **Goal-Oriented Programming** — Choose from **Strength & Power**, **Hypertrophy**, or **Cardio Endurance**.  
- **Rich Exercise Library** — Compound + accessory movements with detailed coaching tips.

<details>
<summary><b>See examples of supported goals & splits</b></summary>

**Goals**
- Strength & Power
- Hypertrophy (Muscle Growth)
- Cardiovascular Endurance

**Splits**
- Individual muscles
- Bro split (Push / Pull / Legs)
- Upper / Lower
- Bodybuilder split
</details>

---

## 🖼️ Demo

▶️ **Live app:** https://neellifts.netlify.app/

> Tip: Click <em>Accept & Begin</em>, then pick your split, muscles, and goal — generate and go!

---

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS  
- **Logic:** JavaScript (ES6)  
- **State:** React Hooks (`useState`)  
- **Styling:** Utility-first CSS with Tailwind  
- **Deploy:** Netlify / Vercel / GitHub Pages (static hosting)

---

## 📂 Project Structure

```text
src/
├── components/
│   ├── Hero.jsx             # Intro section
│   ├── Generator.jsx        # Workout generation logic & UI
│   ├── Workout.jsx          # Displays generated workouts
│   ├── ExerciseCard.jsx     # Exercise details, sets tracker
│   ├── SectionWrapper.jsx   # Section layout helper
│   ├── Button_temp.jsx      # Reusable button
│
├── utils/
│   ├── function.js          # Workout generation algorithm
│   ├── swoldier.js          # Exercise database & training schemes
│
├── App.jsx                  # Main app container
