# Klumora Platform

**Your moments of glory, captured by the best professionals.**

> The UK's premier creator marketplace — where great moments meet elite photographers and videographers. Book instantly, zero upfront fees.

---

## Project Structure

```
klumora-platform/
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
| Kklumora AI | 🔜 Next | Claude API-powered concierge & ETA agent |
| Mobile App | 🔜 Next | React Native (iOS + Android) |

## Tech Stack (Planned)

- **Frontend:** Next.js 14 (App Router) + Tailwind CSS
- **Backend:** Supabase (Postgres + Auth + Storage)
- **Payments:** Stripe Connect (escrow)
- **AI:** Anthropic Claude API (Kklumora AI concierge)
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

*Built with ❤️ · Kklumora Ltd · London, UK · 2026*
