# Finova — Invoice & Receipt SaaS

> A clean, minimal invoice and receipt management app for freelancers and small businesses.

![Finova](https://img.shields.io/badge/Finova-v1.0-009A49?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIyLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI+PHBhdGggZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6Ii8+PHBhdGggZD0iTTggMTJsMi41IDIuNUwxNiA5Ii8+PC9zdmc+)
![Status](https://img.shields.io/badge/Status-MVP-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)

## ✨ Features

- **Authentication** — Sign up / sign in with email & password
- **Dashboard** — Revenue overview, outstanding amount, recent invoices, clients at a glance
- **Invoice Management** — Create, view, filter, and delete invoices
- **Line Items** — Dynamic line items with auto-calculated subtotal, tax (10%), and total
- **Status Tracking** — Draft → Pending → Paid workflow
- **Receipt Generation** — One-click receipt from any paid invoice (print-ready, PDF-ready)
- **Client Directory** — Auto-populated from invoices; manually add clients with full details
- **Search & Filter** — Filter invoices by status; search by client name or invoice ID

## 🚀 Live Demo

👉 **[View Live App](#)** _(deploy link here)_

## 🛠 Tech Stack

| Layer | Choice |
|-------|--------|
| Frontend | Vanilla HTML + CSS + JavaScript (zero dependencies) |
| State | In-memory JS objects |
| Styling | CSS Custom Properties |
| Hosting | GitHub Pages / Netlify / Vercel |

No build step. No npm install. Just open `index.html`.

## 📁 Project Structure

```
finova/
├── index.html          # Full application (single file)
├── README.md           # This file
└── docs/
    ├── PRD.md          # Product Requirements Document
    └── styles.md       # UI Style Guide
```

## 🏃 Running Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/finova.git
cd finova

# Open in browser
open index.html
# or
npx serve .
```

## 🚢 Deploying

### GitHub Pages
1. Push to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app is live at `https://YOUR_USERNAME.github.io/finova`

### Netlify (drag & drop)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `finova/` folder
3. Done — instant live URL

### Vercel
```bash
npx vercel
```

## 📄 Documentation

- [Product Requirements Document](./docs/PRD.md)
- [UI Style Guide](./docs/styles.md)

## 🗺 Roadmap

- [ ] PDF export (jsPDF)
- [ ] Email invoice simulation
- [ ] Invoice filtering by date range
- [ ] LocalStorage persistence
- [ ] Backend + real auth (v2)
- [ ] Stripe payment integration (v2)

## 📝 License

MIT © Finova Team 2025
