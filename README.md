# 🦜 SarawakGo — Sarawak Travel Cost Calculator

> *Estimate your flight & hotel costs to any destination in Sarawak — instantly, beautifully.*

**Built by [AhChaiTrp](https://github.com/AhChaiTrp) · © 2026**

---

## ✦ What is SarawakGo?

**SarawakGo** is a free, single-file travel cost estimator designed exclusively for trips within **Sarawak, Malaysia** — the Land of the Hornbill. No sign-up. No API keys. No backend. Just open the file and plan your trip.

It compares estimated fares across multiple airlines and hotel booking platforms side-by-side, then calculates a full cost breakdown — flight subtotal, hotel subtotal, taxes, service charges — and delivers a **grand total** in Malaysian Ringgit (MYR).

---

## ✈️ Features

- **Airline comparison** across AirAsia, Malaysia Airlines, Batik Air & Firefly
- **Hotel platform comparison** across Agoda, Booking.com, Airbnb & Hotels.com
- **3 travel tiers** — Optimal Budget 🌿, Comfort Travel ✈️, Comfort+ Travel 👑
- **Live deep-links** — every airline and hotel row links directly to their booking page, pre-filled with your route, dates and rooms
- **Cheapest option auto-highlighted** for both flights and hotels
- **Night counter** — auto-calculates nights from check-in/check-out dates
- **Full cost breakdown** — base fares, airport taxes, hotel service charges, subtotals, grand total
- **Live weather forecast** for your destination and travel dates via [Open-Meteo](https://open-meteo.com) (free, no API key) — falls back to a general seasonal climate note for trips beyond the 16-day forecast window
- **Live currency conversion** of your grand total into USD, SGD & GBP via [Frankfurter.dev](https://frankfurter.dev) (free, no API key, ECB reference rates)
- **100% client-side** — pure HTML, CSS, JavaScript. No backend, no build step, no API keys to configure. Works offline for cost estimation; weather/currency features require an internet connection.
- **Sarawak-themed UI** — hand-drawn Rhinoceros Hornbill SVG, jungle-gold colour palette, Cinzel + Playfair Display typography

---

## 🗺️ Supported Routes

| From | To (Sarawak) |
|------|-------------|
| Kuala Lumpur (KUL) | Kuching (KCH) |
| Johor Bahru (JHB) | Miri (MYY) |
| Penang (PEN) | Sibu (SBW) |
| Kota Bharu (KBR) | Bintulu (BTU) |
| Kota Kinabalu (BKI) | Limbang (LMN) |
| Labuan (LBU) | Mukah (MKM) |

---

## 💰 Travel Tiers

| Tier | Flight Class | Hotel Category | Best For |
|------|-------------|----------------|----------|
| 🌿 Optimal Budget | Budget carriers (economy, no frills) | Guesthouses & budget hotels | Backpackers, solo travellers |
| ✈️ Comfort Travel | Mid-tier airlines (economy flex) | 3–4★ business hotels | Couples, small families |
| 👑 Comfort+ Travel | Premium / business class | 5★ luxury resorts | Corporate travel, honeymoons |

---

## 🚀 How to Use

### Run Locally
```bash
git clone https://github.com/AhChaiTrp/sarawakgo.git
cd sarawakgo
open index.html   # macOS
# or just double-click index.html on Windows
```

### Host Free (No server needed)

**Netlify Drop** *(fastest — 2 minutes)*
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag `index.html` onto the page
3. Get a live URL instantly

**GitHub Pages** *(recommended)*
1. Fork this repository
2. Go to **Settings → Pages → Branch: main → Save**
3. Live at `https://yourusername.github.io/sarawakgo`

**Cloudflare Pages** *(best performance for Malaysian users)*
1. [pages.cloudflare.com](https://pages.cloudflare.com) → Upload assets
2. Drop the file → instantly on Cloudflare's global CDN

---

## ⚠️ Disclaimer

Prices shown are **estimates based on average market rates as of 2026**. Actual fares vary by date, seat availability, promotions and airline policy. Always verify the final price on the respective booking platform before purchasing.

Flight and hotel prices are **not** live — they use curated reference pricing updated manually. Weather and currency conversion figures **are** fetched live from free, public, no-key APIs (Open-Meteo & Frankfurter.dev).

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Cinzel, Playfair Display, Outfit |
| Icons | SVG (hand-drawn Rhinoceros Hornbill) |
| Weather data | [Open-Meteo](https://open-meteo.com) — free, no API key |
| Currency rates | [Frankfurter.dev](https://frankfurter.dev) — free, no API key |
| Hosting | Any static host (Netlify / GitHub Pages / Cloudflare) |
| Dependencies | **None** (weather/currency calls are plain `fetch()` to free public APIs — no SDKs, no keys to manage) |

---

## 📁 File Structure

```
sarawakgo/
└── index.html      ← Entire app. One file. That's it.
```

---

## 🤝 Contributing

Pull requests are welcome. If you want to:
- Add more Sarawak destinations (e.g. Marudi, Kapit)
- Update pricing data for accuracy
- Add new airline or hotel platforms
- Translate to Bahasa Malaysia

Fork the repo and submit a PR.

---

## 📄 License

MIT License — free to use, modify and distribute with attribution.

---

<div align="center">

Made with ❤️ for **Sarawak** — *Land of the Hornbill*

**[AhChaiTrp](https://github.com/AhChaiTrp)** · Sarikei, Sarawak, Malaysia · 2026

</div>
