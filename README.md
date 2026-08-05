# Lumora Platform

**The UK's premier photography & videography marketplace.**

> Book world-class photographers and videographers in minutes, or build a thriving creative career — on the platform designed for both sides of the lens.

---

## Project Structure

```
lumora-platform/
├── index.html          # Main landing page
├── pages/
│   └── onboarding.html # Photographer / Videographer onboarding
├── assets/             # Icons, images (future)
└── README.md
```

## Roadmap

| Phase | Status | Description |
|-------|--------|-------------|
| Landing Page | ✅ Done | Full marketing site with AI features, pricing, app mock |
| Onboarding | ✅ Done | Multi-step creator registration flow |
| Search & Booking | 🔜 Next | Real-time search, availability calendar, instant booking |
| Photographer Dashboard | 🔜 Next | Earnings, calendar, bookings management |
| Client Dashboard | 🔜 Next | Booking history, gallery, AI concierge |
| Payments (Stripe) | 🔜 Next | Escrow, auto-release, invoicing |
| Lumora AI | 🔜 Next | Claude API-powered concierge & ETA agent |
| Mobile App | 🔜 Next | React Native (iOS + Android) |

## Tech Stack (Planned)

- **Frontend:** Next.js 14 (App Router) + Tailwind CSS
- **Backend:** Supabase (Postgres + Auth + Storage)
- **Payments:** Stripe Connect (escrow)
- **AI:** Anthropic Claude API (Lumora AI concierge)
- **Media:** Cloudinary (portfolio & gallery delivery)
- **Maps:** Mapbox (location-aware search)
- **Mobile:** React Native (Expo)

## Running Locally

```bash
# Serve the static site
python3 -m http.server 4321 --directory .
# Then open http://localhost:4321
```

---

*Built with ❤️ · Lumora Ltd · London, UK · 2026*
