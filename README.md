# 🍸 Velvet Pour — GSAP Cocktail Experience

A cinematic cocktail landing page built with **React**, **Vite**, **Tailwind CSS**, and **GSAP**.

Velvet Pour is a motion-focused web experience designed to combine immersive visuals, smooth scrolling, animated typography, interactive sections, and cinematic transitions into a single premium landing page.

This project was built to explore how far **React + GSAP** can push modern web interactions beyond simple hover effects and basic animations.

---

## ✨ Features

### 🎬 Cinematic Hero Section

The hero section introduces the experience with a dramatic **MOJITO** title animation powered by GSAP and SplitText.

It includes:

* Character-by-character title animation
* Staggered subtitle animation
* Decorative leaf animations
* Scroll-based parallax movement
* Pinned video section
* Scroll-controlled video playback
* Responsive animation behavior

The hero video progresses according to the user's scroll position, creating a cinematic transition into the rest of the website.

---

### 🍹 Cocktail Showcase

The cocktail section displays a curated collection of popular cocktails and mocktails.

It includes:

* Popular cocktail listings
* Mocktail listings
* Cocktail details
* Pricing
* Scroll-based parallax animations
* Animated decorative elements

The content is generated dynamically from structured data rather than being hardcoded into individual elements.

---

### 🎨 The Art Section

The Art section is designed as a cinematic scroll experience.

As the user scrolls:

1. Supporting content gradually fades away.
2. The central cocktail image scales through a mask animation.
3. The visual focus transitions toward the center.
4. The final message is revealed.

The section uses **ScrollTrigger, pinned scrolling, scrubbed timelines, opacity transitions, scaling, and mask animations**.

---

### 🖼️ About Section

The About section focuses on the story and visual identity of the cocktail brand.

It features:

* SplitText heading animation
* Staggered content reveals
* Animated image grids
* Responsive layouts
* Brand information
* Customer rating presentation

The section combines typography and imagery to create an editorial-style layout.

---

### 🔄 Interactive Cocktail Menu

The cocktail menu is fully interactive.

Users can navigate between cocktails using:

* Cocktail tabs
* Previous cocktail button
* Next cocktail button

When the active cocktail changes:

* The cocktail image changes
* The cocktail name changes
* The title changes
* The description changes
* GSAP animations replay the transition

This combines **React state management with GSAP animation** to create a dynamic browsing experience.

---

### 🧭 Animated Navigation

The navigation starts with a transparent appearance and changes as the user scrolls.

GSAP controls:

* Background transition
* Blur effect
* Scroll-triggered navigation styling

This keeps the navigation visually integrated with the cinematic design.

---

### 📱 Responsive Animations

The animation system also considers different screen sizes.

Using `react-responsive`, animation trigger positions and behavior can be adjusted for mobile and desktop layouts.

This helps maintain the intended experience across different devices.

---

## 🧠 GSAP Techniques Used

This project explores several powerful GSAP techniques:

* **GSAP Timelines**
* **ScrollTrigger**
* **SplitText**
* **Scrubbed animations**
* **Pinned sections**
* **Parallax animations**
* **Staggered animations**
* **Masked image reveals**
* **Scroll-controlled video**
* **Responsive animation logic**
* **React + GSAP integration**
* **`useGSAP()`**

The main goal was to combine these techniques into complete experiences rather than using animations as isolated effects.

---

## 🛠️ Tech Stack

| Technology          | Purpose                        |
| ------------------- | ------------------------------ |
| ⚛️ React            | UI development                 |
| ⚡ Vite              | Development and build tooling  |
| 🎞️ GSAP            | Advanced animations            |
| 🧩 @gsap/react      | GSAP integration with React    |
| 🎨 Tailwind CSS     | Styling and responsive layouts |
| 📱 React Responsive | Responsive animation logic     |
| 🟨 JavaScript / JSX | Application logic              |

---

## 📂 Project Structure

```text
gsap_cocktails/
│
├── public/
│   ├── images/
│   └── videos/
│
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── Cocktails.jsx
│   │   ├── About.jsx
│   │   ├── Art.jsx
│   │   └── Menu.jsx
│   │
│   ├── App.jsx
│   └── ...
│
├── package.json
├── vite.config.js
└── README.md
```

---

## 🚀 Installation & Setup

Want to run the complete project locally?

First, clone the repository:

```bash
git clone https://github.com/Aakash8711/gsap_cocktails.git
```

Move into the project directory:

```bash
cd gsap_cocktails
```

### 1. Install dependencies

```bash
npm install
```

### 2. Install GSAP

```bash
npm install gsap @gsap/react
```

### 3. Start the development server

```bash
npm run dev
```

Vite will start the development server and provide the local URL in your terminal.

Open that URL in your browser and explore the experience.

---

## 🎯 Why I Built This

This project was created as a hands-on exploration of **modern web animation and interaction design**.

Instead of creating a traditional static landing page, I wanted to experiment with how:

**Scroll + Typography + Video + Images + Interaction + Motion**

can work together to create a more immersive web experience.

The project helped me explore concepts such as:

* Animation timing
* Easing
* Scroll-driven storytelling
* Typography animation
* Parallax effects
* Pinned sections
* Mask animations
* Responsive animations
* React state + animation
* Cinematic UI composition

---

## 💡 What This Project Demonstrates

This project demonstrates how **GSAP can be used as an animation system inside a React application**, rather than simply adding a few visual effects.

The combination of React's component architecture and GSAP's animation control makes it possible to build highly interactive interfaces where user actions, application state, and scroll position can all influence the visual experience.

---

## ⭐ Credits

Built with:

**React • GSAP • Vite • Tailwind CSS**

Created as a learning and experimentation project focused on advanced frontend animation and interactive web experiences.

---

# 🍸 Thank You

Thank you for checking out **Velvet Pour**.

Keep building. Keep experimenting. Keep pushing the browser a little harder. 🚀

**Thank you! 🍸✨**
