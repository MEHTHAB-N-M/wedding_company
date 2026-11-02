---
title: Wedding Company
emoji: 💍
colorFrom: yellow
colorTo: pink
sdk: static
pinned: false
---

<div align="center">

# 💍 Wedding Company Website

A responsive, elegant, and modern web application for a luxury wedding planning and event management company, built with React 19 and Vite.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://mehthab07-wedding-company.static.hf.space/index.html)
[![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Hugging Face Spaces](https://img.shields.io/badge/Space-Mehthab07%2Fwedding--company-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Mehthab07/wedding-company)

[Live Demo](https://mehthab07-wedding-company.static.hf.space/index.html) · [Hugging Face Space](https://huggingface.co/spaces/Mehthab07/wedding-company) · [Report Bug](https://github.com/MEHTHAB-N-M/wedding_company/issues) · [Request Feature](https://github.com/MEHTHAB-N-M/wedding_company/issues)

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Screenshots](#-screenshots)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Available Scripts](#-available-scripts)
- [Deployment](#-deployment)
- [Author](#-author)

---

## 📖 Overview

**Wedding Co.** is a complete, full-featured web platform crafted for a luxury wedding planning and event management firm. It presents prospective couples with everything they need to plan their special day: curated service offerings, tiered pricing packages, a high-resolution photo portfolio, trusted vendor directories, client testimonials, an interactive appointment reservation form, and a password-protected administrative overview.

Built with **React 19**, styled using custom gold & slate-gray design tokens, and bundled with **Vite**, the application delivers near-instant page loads and smooth client-side routing.

---

## 📸 Screenshots

| Home | Gallery |
| :---: | :---: |
| ![Home](docs/screenshots/home.png) | ![Gallery](docs/screenshots/gallery.png) |

| Services | Contact |
| :---: | :---: |
| ![Services](docs/screenshots/service.png) | ![Contact](docs/screenshots/contact.png) |

---

## ✨ Features

- 📱 **Fully Responsive Design**: Optimized fluid layout across mobile, tablet, laptop, and desktop viewports with a collapsible navigation drawer.
- 💼 **Curated Services Showcase**: Highlights 6 core services (Full Planning, Floral & Decor, Photography & Video, Catering, Entertainment, Bridal Styling) with hover micro-interactions.
- 💎 **Tiered Wedding Packages**: Detailed comparison of Silver, Gold, and Platinum packages with transparent pricing, deliverables, and direct booking links.
- 🖼️ **Interactive Photo Gallery**: Curated visual portfolio of wedding moments featuring image scaling animations.
- 📅 **Online Appointment Booking**: Dedicated consultation reservation form with tentative date picker and service selection.
- 🤝 **Trusted Partner Directory**: Curated vendor list featuring top photographers, florists, caterers, and DJs.
- 💬 **Testimonials & FAQs**: Social proof from couples and answers to frequently asked wedding planning questions.
- 📞 **Direct WhatsApp Integration**: Persistent floating WhatsApp widget for instant, real-time client consultations.
- 🔐 **Protected Admin Dashboard**: Password-authenticated administrative view displaying live metrics (total bookings, pending inquiries, new reviews).
- 🔍 **Dynamic SEO Management**: Per-page document title and meta description injection powered by `react-helmet-async`.
- ⚡ **Optimized Performance**: Production asset hashing, tree-shaking, and fast compilation with Vite.

---

## 🧱 Tech Stack

| Layer | Technology | Details |
| :--- | :--- | :--- |
| **Core Framework** | React 19 (`^19.2.0`), React DOM | Component-driven architecture |
| **Language** | JavaScript (ES6+) | Modern standard syntax |
| **Routing** | React Router DOM v7 (`^7.13.0`) | Client-side SPA routing with 12 configured routes |
| **Styling & Theme** | Vanilla CSS3 | Custom CSS variables (Gold `#D4AF37`, Slate `#2F4F4F`, Misty Rose `#FFE4E1`) |
| **Icons & UI** | Lucide React (`^0.563.0`) | Modern SVG icons |
| **Animations** | Framer Motion (`^12.33.0`) | Smooth transitions and keyframe fade-ins |
| **SEO & Head** | React Helmet Async (`^2.0.5`) | Dynamic per-route `<title>` and `<meta>` tags |
| **Build Tool** | Vite (`^7.2.4`) | High-speed ESM bundler and dev server |
| **Hosting** | Hugging Face Spaces | Static HTML space with automated Vite build & SPA HashRouter |

---

## 📂 Project Structure

```text
wedding_company/
├── docs/
│   └── screenshots/              # Visual previews (home.png, gallery.png, service.png, contact.png)
├── public/                       # Static public assets
├── src/
│   ├── assets/                   # Static media and component assets
│   ├── components/               # Reusable global layout elements
│   │   ├── Footer.jsx            # Multi-column footer with social links & newsletter
│   │   ├── Navbar.jsx            # Sticky navigation header with mobile toggle
│   │   └── WhatsAppWidget.jsx    # Floating WhatsApp quick-contact button
│   ├── pages/                    # 12 distinct application views
│   │   ├── About.jsx             # Company story, values, and milestone stats
│   │   ├── Admin.jsx             # Password-protected admin metrics dashboard
│   │   ├── Booking.jsx           # Online appointment booking form
│   │   ├── Contact.jsx           # Contact information & message inquiry form
│   │   ├── FAQ.jsx               # Frequently asked questions list
│   │   ├── Gallery.jsx           # Portfolio photo gallery
│   │   ├── Home.jsx              # Hero banner, value propositions & highlights
│   │   ├── Packages.jsx          # Silver, Gold, Platinum pricing cards
│   │   ├── Privacy.jsx           # Privacy policy and terms overview
│   │   ├── Services.jsx          # Comprehensive 6-service offerings grid
│   │   ├── Testimonials.jsx      # Client feedback and star reviews
│   │   └── Vendors.jsx           # Directory of trusted vendor partners
│   ├── App.css                   # App container styles
│   ├── App.jsx                   # Central routing definition (`<Routes>`)
│   ├── index.css                 # Global design system, typography & responsive rules
│   └── main.jsx                  # React DOM root entry point
├── eslint.config.js              # ESLint configuration
├── index.html                    # Root HTML document with viewport meta
├── package.json                  # Dependencies, scripts, and overrides
└── vite.config.js                # Vite configuration with React plugin and relative base
```

---

## 🚀 Getting Started

### Prerequisites

- **[Node.js 18+](https://nodejs.org/)**
- **npm** (comes bundled with Node.js)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MEHTHAB-N-M/wedding_company.git
   cd wedding_company
   ```

2. **Install project dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm run dev
   ```

   Open `http://localhost:5173` in your browser.

---

## 🛠️ Available Scripts

In the project directory, you can run:

| Command | Action / Purpose |
| :--- | :--- |
| `npm run dev` | Starts the Vite development server with Hot Module Replacement (HMR) |
| `npm run build` | Compiles and minifies the app into `dist/` for production |
| `npm run preview` | Locally serves the production build from `dist/` |
| `npm start` | Previews the production build with `--host` enabled for network access |
| `npm run lint` | Analyzes code quality and syntax with ESLint |

---

## ☁️ Deployment

The project is pre-configured for deployment on **Hugging Face Spaces** using the **Static** Space SDK (no Docker required).

### Deploying to Hugging Face Spaces

#### Option A: Direct Push to Hugging Face Space Repository

1. **Create a new Space on Hugging Face:**
   - Go to [huggingface.co/new-space](https://huggingface.co/new-space).
   - Enter your Space name (e.g., `wedding-company`).
   - Select **Static** as the Space SDK.
   - Choose **Public** or **Private**.
   - Click **Create Space**.

2. **Add Hugging Face as a Git remote:**
   ```bash
   git remote add space https://huggingface.co/spaces/<YOUR_HF_USERNAME>/<YOUR_SPACE_NAME>
   ```

3. **Push to your Space:**
   ```bash
   git push space main
   ```
   *(If prompted for password, provide your Hugging Face Access Token with **Write** permission from [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)).*

4. Hugging Face reads the configuration from the top of [`README.md`](./README.md), automatically executes `npm run build`, and serves the live application from `dist/index.html`.

#### Option B: Syncing from GitHub

1. In your Hugging Face Space settings, you can link your **GitHub repository** or configure a GitHub Action to automatically push changes to your Hugging Face Space repository upon each commit.

---

## 👨‍💻 Author

**Mehthab N M** — *Full-Stack & Python Developer*

- 🌐 **Portfolio:** [mehthab-n-m.github.io/My_portfolio](https://mehthab-n-m.github.io/My_portfolio/)
- 🐙 **GitHub:** [@MEHTHAB-N-M](https://github.com/MEHTHAB-N-M)
- 💼 **LinkedIn:** [in/mehthab-n-m-637611344](https://www.linkedin.com/in/mehthab-n-m-637611344)

---

<div align="center">

⭐ If you found this project helpful or inspiring, please consider giving it a star!

</div>
