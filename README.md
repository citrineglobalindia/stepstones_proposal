# Stepstones Proposal Studio

A single-file, no-build proposal microsite + admin editor for digital agencies — built for **Stepstones**.

Live demo: open `index.html` in any modern browser.

## What it is

A self-contained HTML/CSS/JS app that lets you:

1. **Author a proposal** in a clean admin panel — fill in client info, services, deliverables, timeline, pricing, terms.
2. **Send the proposal** as a beautifully designed scrollytelling microsite — Apple-product-page-grade typography, scroll-linked animations, industry-specific themes.
3. **Customise every section** — heading text (with bracket-syntax italic accents), description (rich text with bullets / bold / italic), background colour or gradient, layout.
4. **Share via WhatsApp / Email** — the proposal data is encoded in the URL hash so any link is a complete shareable microsite — no backend required.

## Features

- **9 industry themes** — Citrine (Tech), Interior Design, Construction, IT, Real Estate, Hotel, Restaurant, Healthcare, Fashion. Each ships with sample data.
- **Per-section editor** — Each microsite section has its own accordion in the admin form (Requirements, About Your Business, What We Deliver, Timeline, Investment, Terms, Why Citrine, Accept & Begin). Edit heading, italic accent (bracket syntax), description (rich text), and background colour/gradient.
- **Logo uploader** — File upload, drag-and-drop, or paste a URL. Stored as a data URL so it travels with the proposal.
- **Advanced background picker** — Tabbed (Solid Colour / Gradient), live preview, 16 solid presets, 10 gradient presets, full custom colour + gradient builder with angle dial.
- **3-vector cycling hero** — Each industry has 3 business-explaining vector illustrations that auto-cycle on the right side of the hero with industry-specific accents.
- **Industry-themed vectors** — SaaS dashboards (tech), construction blueprints, property listings (real estate), reception scenes (hotel), restaurant menus, telemedicine apps (healthcare), boutique storefronts (fashion), etc.
- **Floating glass nav** — Modern Linear/Framer-style pill nav with scroll-shrink, active section highlight, and animated mobile hamburger overlay menu.
- **Multi-step Accept flow** — Client fills name → signs (type or draw on canvas) → reviews → accepts. Confetti on success. Pre-filled WhatsApp + email to send confirmation back to the agency.
- **Mobile-responsive** — All sections reflow gracefully down to 380px width.
- **Save / Load** — Stores proposals in the browser's localStorage. Shareable URL contains the proposal data.

## How to use

1. Open `index.html` in a browser.
2. Use the admin form on the left to fill in proposal details. Right-side preview updates live.
3. Click **Industry Samples** in the top bar to start from one of 9 ready-made templates.
4. Click **Open Microsite** to view the full client-facing experience in a new tab.
5. Click **Send Proposal** to copy a shareable link or fire it off via WhatsApp / Email.

## Tech

- Pure HTML / CSS / vanilla JavaScript — no framework, no build step
- Google Fonts (Inter Tight, Fraunces, Instrument Serif, Manrope, Bebas Neue, Space Grotesk, DM Mono, Caveat, Anton)
- [Motion One](https://motion.dev) (loaded via CDN) for spring animations and scroll-triggered reveals
- Unsplash images for industry hero photography (referenced via URL)

## Deploy

Easiest way: GitHub Pages.

1. Push this repo to GitHub.
2. Go to **Settings → Pages → Branch: `main` / `(root)` → Save**.
3. Within a minute your proposal app is live at `https://<your-username>.github.io/<repo-name>/`.

Or just upload `index.html` to any static host — Netlify, Vercel, Cloudflare Pages, your own S3 bucket. No build required.

A live deployment is hosted on Vercel.

## License

MIT — see [LICENSE](LICENSE).

---

Designed & developed by **Stepstones**.
