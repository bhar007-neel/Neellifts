🏋️‍♂️ Neelnormous – AI-Powered Workout Generator
Neelnormous is an interactive, browser-based workout generator that helps you create customized training plans based on your fitness goals, target muscle groups, and preferred workout style. Built with React, it dynamically generates workouts using a curated exercise database, ensuring variety, progression, and personalization.

🚀 Features
Custom Workout Generation
Select your workout type (“poison”), target muscle groups, and fitness goal to instantly get a tailored workout plan.

Dynamic Exercise Cards
View exercise descriptions, targeted muscles, recommended reps, rest times, and tempo.

Progress Tracking
Mark sets as completed to keep track of your progress during your workout.

Multiple Training Styles
Supports bro splits, upper/lower splits, individual muscle training, and more.

Goal-Oriented Programming
Choose from:

Strength & Power

Hypertrophy (Muscle Growth)

Cardiovascular Endurance

Rich Exercise Library
Pulls from an extensive dataset of compound and accessory exercises with detailed descriptions.

🖼️ Demo

(https://neellifts.netlify.app/)

🛠️ Tech Stack
Frontend: React, Tailwind CSS

Logic: JavaScript ES6

State Management: React useState Hooks

Styling: Utility-first CSS with Tailwind

Deployment: Static site hosting (Netlify, Vercel, GitHub Pages, etc.)

📂 Project Structure
php
Copy
Edit
src/
├── components/
│   ├── Hero.jsx            # Intro section
│   ├── Generator.jsx       # Workout generation logic & UI
│   ├── Workout.jsx         # Displays generated workouts
│   ├── ExerciseCard.jsx    # Displays each exercise with details
│   ├── SectionWrapper.jsx  # Section layout
│   ├── Button_temp.jsx     # Reusable button component
│
├── utils/
│   ├── function.js         # Workout generation algorithm
│   ├── swoldier.js         # Exercise & scheme data
│
├── App.jsx                 # Main app container
