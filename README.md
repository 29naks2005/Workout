# WorkoutWise

WorkoutWise is a premium and interactive fitness web application designed to help users track, calculate, and improve their fitness journey. Built using modern web technologies, it delivers a seamless, fast, and visually polished experience.

---

## Overview

WorkoutWise provides curated workout routines and essential fitness calculators within a clean and responsive interface. The application focuses on performance, usability, scalability, and premium design aesthetics.

---

## Core Features

### Interactive Home Page
- Engaging hero banner  
- Overview of offerings  
- Highlighted fitness routines  
- Motivational call-to-action section  

### Dedicated Workouts Page
- Structured workout plans  
- Fitness tips  
- Exercise-specific guidance  

### Smart Calculators
- BMI Calculator  
- Maintenance Calories Calculator  
- Instant metric calculation without leaving the app  

### Responsive Premium Design
- Glassmorphism-inspired dark theme  
- Smooth UI animations  
- Optimized layouts for desktop, tablet, and mobile  

### Fast Navigation
- Client-side routing powered by React Router DOM  
- Instant and seamless page transitions  

---

## Tech Stack

| Category        | Technology Used |
|----------------|----------------|
| Frontend Core  | React 19 |
| Routing        | React Router DOM v7 |
| Styling        | Vanilla CSS (Custom Flexbox & Grid, Animations, Dark Mode UI) |
| Build Tool     | Vite |

---

## Installation & Setup

### Prerequisites

Ensure you have Node.js installed.

### 1. Clone the Repository

```bash
git clone <repository-url>
cd workoutwise
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start Development Server

```bash
npm run dev
```

### 4. Open in Browser

Visit:

```
http://localhost:5173
```

---

## Build for Production

```bash
npm run build
```

Preview production build locally:

```bash
npm run preview
```

---

## Project Structure

```
src/
├── assets/              # Static assets (images, icons, etc.)
├── components/          # Reusable UI components
│   ├── Navbar
│   ├── Footer
│   ├── HeroSlider
│   ├── BMICalculator
│   ├── WhatWeOffer
│   ├── StartSection
│   └── WorkoutHighlight
├── pages/               # Route-level components
│   ├── Home.jsx
│   └── Workouts.jsx
├── App.jsx              # Routes configuration
├── App.css              # Global styles
└── main.jsx             # Application entry point
```

---

## Design Philosophy

WorkoutWise follows a clean and scalable component-based architecture with a strong focus on:

- Maintainable folder structure  
- Performance optimization  
- Modern UI patterns  
- Smooth user experience  

---

## Author

Developed by Nakul Sharma
