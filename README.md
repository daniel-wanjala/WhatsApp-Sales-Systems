# Ndubi — WhatsApp Sales Systems for Kenyan Businesses

A high-converting, single-page marketing website for **Ndubi**, a WhatsApp automation and paid ads specialist based in Nairobi, Kenya. Built with pure HTML and CSS — no frameworks, no dependencies, no build step.

---

## 🚀 Live Preview

Open `index.html` directly in your browser. No server required.

---

## 📁 Project Structure

```
ndubi/
├── index.html        # The entire site — HTML, CSS, and inline styles
├── README.md         # You're reading it
├── LICENSE           # MIT License
└── .gitignore        # Files excluded from version control
```

---

## ✨ Features

- **Animated ticker bar** — scrolling social proof at the top
- **Hero section** with profile stat card
- **Problem/pain section** with bold statistics
- **Live WhatsApp chat mockup** — animated to simulate a real conversation
- **Offer cards** — WhatsApp Flow Setup + Meta & TikTok Ads + Bundle deal
- **How It Works** — 4-step process breakdown
- **Testimonials** — 3 client result cards
- **FAQ** — native HTML `<details>` accordion, no JS needed
- **Footer CTA** — direct WhatsApp deep link
- **Fully responsive** — mobile-first breakpoints at 900px

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--black` | `#070709` | Page background |
| `--off-white` | `#f0ede6` | Body text |
| `--green` | `#00e87a` | Brand accent, CTAs |
| `--green-dim` | `#00b85e` | Hover states |
| `--slate` | `#1a1d27` | Card backgrounds |
| `--muted` | `#5a5f72` | Secondary text |

**Fonts (Google Fonts):**
- `Syne` (800, 700, 400) — headings, logos, buttons
- `DM Sans` (300, 400, 500, italic) — body text

---

## 🛠️ Tech Stack

- **Pure HTML5** — semantic structure
- **Pure CSS3** — custom properties, grid, flexbox, keyframe animations
- **Zero JavaScript** — animations via CSS, accordion via native `<details>`
- **Google Fonts** — loaded via `<link>` in `<head>`
- **WhatsApp deep links** — `wa.me` URLs with pre-filled messages

---

## 📱 WhatsApp Links

All CTA buttons link to:
```
https://wa.me/254736127284?text=...
```
To update the phone number, find and replace `254736127284` with your number (include country code, no `+`).

---

## 🔧 Customisation

**Change prices:** Search for `KES 10,000` / `KES 16K` and update the values.

**Change stats (hero card):** Find `.profile-stats` and edit the `.stat-num` divs.

**Change testimonials:** Find `.testimonials` and edit the `.t-card` blocks.

**Change business niche:** Update copy in the hero, demo, and FAQ sections.

**Add your own avatar/photo:** Replace the `<div class="profile-avatar">N</div>` with an `<img>` tag.

---

## 📦 Deployment

This is a static site. Deploy anywhere:

- **GitHub Pages** — push to `main`, enable Pages in repo settings
- **Netlify** — drag and drop the folder
- **Vercel** — import the repo
- **Cloudflare Pages** — connect GitHub repo

No build command needed. Publish directory: `/` (root).

---

## 📄 License

MIT — see `LICENSE` for details.

---

## 👤 Author

Built for **Ndubi** — WhatsApp Automation & Paid Ads Specialist · Nairobi, Kenya.
