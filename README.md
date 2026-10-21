# NexBank 🏦 — Modern Banking Single Page Application

<p align="center">
  <img src="https://i.postimg.cc/rwzKBrsQ/NexBank.png" alt="NexBank Website Preview" width="100%" />
</p>

<p align="center">
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=black&style=for-the-badge" alt="React" /></a>
  <a href="https://vitejs.dev/"><img src="https://img.shields.io/badge/Vite-6.3.5-646CFF?logo=vite&logoColor=white&style=for-the-badge" alt="Vite" /></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-3.2.7-06B6D4?logo=tailwindcss&logoColor=white&style=for-the-badge" alt="Tailwind CSS" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License: MIT" /></a>
</p>

---

## 📌 Overview

**NexBank** is a modern, responsive Single Page Application (SPA) business website designed for modern banking and fintech platforms. Built with **React 18**, **Tailwind CSS**, and bundled with **Vite**, it delivers ultra-fast load times, sleek dark-themed UI aesthetics, and modular component architecture.

---

## ✨ Features

- **Responsive Modern Design:** Fully responsive layout with mobile-optimized hamburger navigation drawer and desktop navigation bar.
- **Hero Section:** Value proposition header featuring interactive "Get Started" prompt, dynamic gradient styling, and key statistical counters ($230M+ transactions, 3,800+ active users, 230+ trusted partners).
- **Business Highlights:** Feature highlight cards emphasizing rewards, 100% security encryption, and streamlined balance transfers.
- **Billing & Invoice Showcase:** Interactive preview showcasing seamless billing, transaction management, and mobile app download integration (App Store & Google Play).
- **Card Deals & Solutions:** Overview of credit card offerings with direct call-to-action buttons.
- **Client Testimonials:** High-fidelity feedback cards showcasing customer reviews and quotes.
- **Partner Showcase:** Partner brand showcase featuring industry leaders (Airbnb, Binance, Coinbase, Dropbox).
- **Call-to-Action (CTA):** High-converting CTA section to onboard users quickly.
- **Comprehensive Footer:** Structured resource links (Useful Links, Community, Partners) and social media connectivity (LinkedIn, Facebook, Instagram, Twitter/X).

---

## 🛠️ Tech Stack

- **Frontend Framework:** [React 18](https://react.dev/)
- **Build Tool / Bundler:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) & [PostCSS](https://postcss.org/)
- **Icons & Assets:** Custom SVGs, WebP graphics, and vector assets

---

## 📂 Project Structure

```text
NexBank-SPA/
├── public/                 # Static public assets (vite.svg)
├── src/
│   ├── assets/             # Brand logos, icons, card graphics, avatars
│   ├── components/         # Reusable React UI components
│   │   ├── Billing.jsx     # Billing & invoice management section
│   │   ├── Business.jsx    # Value proposition & features list
│   │   ├── Button.jsx      # Reusable styled button component
│   │   ├── CardDeal.jsx    # Card offers & deals section
│   │   ├── Clients.jsx     # Brand client logos section
│   │   ├── CTA.jsx         # Call to action section
│   │   ├── Feedback.jsx    # Individual testimonial card component
│   │   ├── Footer.jsx      # Navigation links and social icons footer
│   │   ├── GetStarted.jsx  # Circular interactive hero action button
│   │   ├── Hero.jsx        # Primary hero banner
│   │   ├── Navbar.jsx      # Responsive navigation header
│   │   ├── Stats.jsx       # Numerical impact metrics
│   │   └── Testimonials.jsx# Feedback container section
│   ├── constants/          # Static content, links, and text datasets
│   │   └── index.js
│   ├── App.jsx             # Main layout and view assembly
│   ├── index.css           # Global Tailwind and font styles
│   ├── main.jsx            # Application entry point
│   └── style.js            # Centralized layout style constants
├── index.html              # HTML entry template
├── package.json            # Project dependencies and run scripts
├── postcss.config.cjs      # PostCSS configuration
├── tailwind.config.cjs     # Tailwind theme and breakpoint configuration
└── vite.config.js          # Vite configuration
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (version `18.x` or later recommended)
- [npm](https://www.npmjs.com/) (version `9.x` or later) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Praful958/NexBank-SPA.git
   cd NexBank-SPA
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

### Running Locally

To start the Vite local development server with Hot Module Replacement (HMR):
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### Building for Production

To compile and bundle the application into the `dist/` directory:
```bash
npm run build
```

To preview the production build locally:
```bash
npm run preview
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
Original template created by [Muhammad Tanveer Abbas](https://github.com/).
