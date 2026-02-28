# Wittness Tech - Bespoke Software Solutions for SMEs

📈 **Crafting custom software to power your business growth**

## About Us

At **Wittness Tech**, we build **tailor-made software solutions** for SMEs. Our website ([wittness.tech](https://wittness.netlify.app/)) is a lightweight, performant showcase built with **Vite + Tailwind CSS + Alpine.js**.

## Features

- ✔ **Custom Web Apps**
- ✔ **Process Automation**
- ✔ **E-Commerce Solutions**
- ✔ **Data Analytics**

## Tech Stack

- **Build**: Vite
- **Styling**: Tailwind CSS v4
- **Interactivity**: Alpine.js
- **Deployment**: Static files (dist folder)

## Quick Start

```bash
# Install dependencies
npm install

# Development (hot reload)
npm run dev

# Production build
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
wittness/
├── src/
│   ├── index.html       # Main HTML
│   ├── main.js          # Alpine.js entry
│   ├── style.css        # Tailwind + custom styles
│   ├── js/              # Local JS libs
│   ├── css/             # AOS animations
│   ├── fonts/           # Custom fonts
│   └── img/             # Images
├── public/              # Static assets (fonts, extra images)
├── dist/                # Production build (deploy this)
├── vite.config.js       # Vite configuration
└── package.json
```

## Deployment

Build the project and upload the `dist/` folder to any static host:

```bash
npm run build
# Deploy dist/ folder
```

### Netlify/Vercel
- Connect your repo
- Build command: `npm run build`
- Output directory: `dist`

### Traditional (cPanel, Apache, Nginx)
- Upload `dist/` contents to `public_html`

---

🕴️ [wittness.tech](https://wittness.netlify.app/)

✍️ hello@wittness.tech

---

© 2024-25 Wittness Tech. All rights reserved.
