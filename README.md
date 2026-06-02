# ARIO — We Engineer Experiences

A high-energy, visually striking landing page for **ARIO**, a premier event management company based in **Ipoh, Perak, Malaysia**.

Built as a single-page, fully self-contained HTML file, this landing page delivers a modern, premium brand experience inspired by high-performance motorsport and fashion aesthetics — oversized typography, neon accents, dark mode UI, and smooth scroll-triggered animations.

---

## ✨ Features

- **Immersive Hero Section** — Full-screen background with dark gradient overlay and bold neon headline.
- **Sticky Glass Navigation** — Transparent frosted-glass nav bar that solidifies on scroll, with animated link underlines.
- **Infinite Marquee** — Neon scrolling text ribbon showcasing service categories (Corporate Galas, Music Festivals, Brand Activations, Private VIP Parties).
- **Services Grid** — Sleek dark cards with neon left-border hover effects, icons, and descriptions.
- **Featured Events Gallery** — Image cards with overlay hover animations revealing event details and links.
- **Call-to-Action Section** — Massive neon email link and "Plan Your Event" button.
- **Mobile-Responsive** — Fully responsive layout with hamburger mobile menu.
- **Scroll Animations** — GSAP-powered fade-in and slide-up animations triggered on scroll.

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure |
| **Tailwind CSS** (CDN) | Utility-first styling framework |
| **GSAP** (CDN) | Scroll-triggered animations & transitions |
| **Font Awesome 6** (CDN) | Icons |
| **Vanilla JavaScript** | Mobile menu toggle, sticky nav behaviour |

All dependencies are loaded via CDN — **no build tools or package managers required**.

---

## 📁 Project Structure

```
Landing Page mock up - Copy/
├── index.html                   # Main landing page (single-file SPA)
├── README.md                    # Project documentation (this file)
├── VERCEL_DEPLOY_GUIDE.md       # Deployment guide for Vercel
└── event_management_agent_prompt.md  # Original design brief / system prompt
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ario-landing-page.git
   cd ario-landing-page
   ```

2. **Open the landing page**
   - Simply open `index.html` in any modern web browser.
   - No server or build step required.

3. **Customise**
   - Replace placeholder images with your own event photography (search for `source.unsplash.com` in `index.html`).
   - Update contact email, social media links, and company info in the CTA and footer sections.
   - Adjust brand colours via the `:root` CSS variables at the top of the `<style>` block.

---

## 🌐 Deployment

This is a static HTML site and can be deployed to any hosting platform:

- **Vercel** — See [`VERCEL_DEPLOY_GUIDE.md`](./VERCEL_DEPLOY_GUIDE.md) for step-by-step instructions.
- **Netlify** — Drag & drop the folder or connect your Git repo.
- **GitHub Pages** — Push to a `gh-pages` branch or use the root of a `username.github.io` repo.
- **Any static host** — Upload the contents of this folder to any web server.

---

## 🎨 Design Highlights

- **Colour Palette:**
  - Background: `#000000` (pitch black) / `#111111` (dark cards)
  - Accent: `#DFFF00` (neon yellow) with a subtle glow
  - Text: `#FFFFFF` (primary) / `#A3A3A3` (secondary)
- **Typography:**
  - Headings: **Oswald** (bold, uppercase, condensed)
  - Body: **Inter** (clean, highly legible sans-serif)
- **UI Patterns:**
  - Neon borders that appear on hover
  - Image scale-up on hover for event cards
  - Frosted glass (`backdrop-filter: blur`) nav bar
  - Smooth fade & slide-up animations via GSAP ScrollTrigger

---

## 📄 License

This project is provided for demonstration and educational purposes.  
Feel free to use and adapt it for your own event management brand.

---

Built with ❤️ for ARIO — Ipoh, Perak.