# Voice-O-Magic Website — Gold Professional Theme

## Vercel Free Deployment Guide

### Step 1: Add Your Images
Place these two image files in the root of this folder (same level as `index.html`):
- `logo.png`
- `shalini-mukund.jpg`

### Step 2: Deploy to Vercel (3 ways)

#### Option A — Vercel CLI (Fastest)
```bash
npm i -g vercel
vercel
```

#### Option B — Git + Vercel Dashboard
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → "Add New Project"
3. Import your repo
4. Framework Preset: **Other** (static)
5. Click **Deploy**

#### Option C — Vercel Drag & Drop
1. Go to [vercel.com](https://vercel.com)
2. Drag this entire folder onto the Vercel dashboard
3. Done — instant live URL

### Step 3: Custom Domain (Optional)
In your Vercel project settings → Domains → Add your custom domain.

---

## Features

- **Dark / Light Mode Toggle** — Persistent via localStorage, respects system preference
- **Gold, White, Black Theme** — Balanced, professional, no over-light or dark extremes
- **8 Pages** — Home, About, Keynotes, Academy, Corporate, Books, Resources, Contact
- **WhatsApp Contact Form** — Validates and redirects to WhatsApp with pre-filled message
- **Video Modal** — Embedded YouTube player
- **Resource Downloads** — Modal-based lead capture
- **Mobile Responsive** — Fully responsive with hamburger menu

## Tech Stack
- HTML5 (semantic, accessible)
- Tailwind CSS via CDN
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts (Inter + Playfair Display)
- Custom CSS with CSS Variables for theme switching
