# SmartDine - Restaurant Payment Platform

A modern, responsive landing page for SmartDine, a cutting-edge restaurant payment and ordering platform built with **Tailwind CSS**. Features a mobile-first responsive design, Lottie mascot integration, and seamless dark/light theme switching.

## 🚀 Live Demo

**[View Live Demo →](https://tum-web-lab2-bice.vercel.app)**

## 📖 About

SmartDine is a comprehensive solution designed for modern restaurants, enabling:
- **Instant QR code-based ordering** directly from tables
- **Smart bill splitting** with support for Apple Pay and Google Pay
- **Real-time analytics** for data-driven business decisions
- **Integrated loyalty programs** to boost customer retention

This landing page showcases the platform's features with a mobile-first responsive layout, Tailwind CSS utility classes, a Lottie chef mascot, and cosmic-themed dark mode design with smooth animations.

## ✨ Features

- 🎨 **Dark/Light Mode Toggle** — Seamless theme switching with localStorage persistence (synced desktop + mobile)
- 📱 **Mobile-First Responsive Design** — Tailwind CSS breakpoints (sm/md/lg) with mobile-specific elements
- 🍳 **Lottie Chef Mascot** — Animated mascot with 3s delay entrance, hover speech bubble, and dismissible UI
- 🎠 **Infinite Carousel Animation** — Smooth scrolling feature showcase with hover-to-pause
- 📲 **Mobile-Only Elements** — QR badge, app download banner, sticky CTA, and hamburger menu
- ⚡ **Modern Animations** — Fade-in-up, floating stats, bounce-in mascot, and carousel marquee
- 🎯 **Clean UI/UX** — Glassmorphism cards, responsive pricing grid, and accessible touch targets
- 📊 **Interactive Sections** — Pricing cards, testimonials, FAQ, and newsletter signup
- 🔤 **Custom Typography** — Inter font family with responsive sizing scale

## 🛠️ Technologies Used

- **Tailwind CSS** — Utility-first CSS framework (CDN with custom config)
- **HTML5** — Semantic markup with responsive meta viewport
- **CSS3** — Custom properties for theming, companion stylesheet for complex components
- **Vanilla JavaScript** — Theme toggle, mobile menu, mascot interactions
- **Lottie Web** — `@lottiefiles/lottie-player` for chef mascot animation
- **Font Awesome 6.5.1** — Professional icon library via CDN
- **Google Fonts** — Inter typeface (weights 300–800)
- **Vercel** — Deployment platform with automatic deploys

## 🎯 Sections

1. **Header** — Fixed navbar with responsive hamburger menu and theme toggle
2. **Hero** — Eye-catching introduction with phone mockup, mobile-only QR badge, and CTA buttons
3. **Mobile Banner** — App download prompt (mobile-only)
4. **Features** — Infinite carousel with 4 feature cards (duplicated for seamless scroll)
5. **How It Works** — Benefits checklist with animated floating stat cards
6. **Pricing** — Three-tier responsive grid (Starter, Growth, Enterprise) with featured highlight
7. **Testimonials** — Customer success stories in card layout
8. **FAQ** — Common questions in responsive two-column grid
9. **Footer** — Links, newsletter signup, and copyright
10. **Mobile Sticky CTA** — Fixed bottom call-to-action (mobile-only)
11. **Chef Mascot** — Lottie animation with speech bubble and dismiss functionality

## 🚀 Deployment

The site is deployed on Vercel with automatic deployments on every push to the master branch.

```bash
# Deploy with Vercel CLI
vercel

# Or push to GitHub and let Vercel handle it automatically
git push origin master
```

## 📝 Development

```bash
# Clone the repository
git clone https://github.com/caramisca/tum-web-lab2.git

# Navigate to project
cd tum-web-lab2

# Open in browser
# (No build process required - static site)
```

## 📁 Project Structure

```
tum-web-lab2/
├── index.html              # Main page (Tailwind CSS + responsive layout)
├── style.css               # Companion stylesheet (theme vars, carousel, mascot)
├── Chef animation.json     # Lottie mascot animation data
├── vercel.json             # Vercel deployment config
├── README.md               # Project documentation
└── screenshots/            # App mockup images
```

## 🎨 Color Palette

**Dark Mode (Default)**
- Background: `#050507` (Deep cosmic black)
- Primary: `#ffffff` (White)
- Accent: `#38bdf8` (Cyan glow)
- Text: `#f1f5f9` (Light gray)

**Light Mode**
- Background: `#f8fafc` (Off-white)
- Primary: `#0f172a` (Dark slate)
- Text: `#1f2937` (Dark gray)

## 📱 Responsive Breakpoints

| Breakpoint | Width  | Target       |
|------------|--------|-------------|
| Default    | < 640px | Mobile      |
| `sm:`      | ≥ 640px | Large phone |
| `md:`      | ≥ 768px | Tablet      |
| `lg:`      | ≥ 1024px| Desktop     |

## 📄 License

This project is part of a web development course assignment (Lab 2 → Lab 3).

## 👨‍💻 Author

**Caramisca**
- GitHub: [@caramisca](https://github.com/caramisca)

---
