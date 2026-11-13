# 🦜 SarawakGo — Sarawak Trip Cost Planner

> *Plan your Sarawak trip and know the full cost before you go.*

**Built by AhChai · © 2026**

**Live:** [trulypureman.github.io/sarawakgo](https://trulypureman.github.io/sarawakgo)

---

## ✦ What is SarawakGo?

SarawakGo is a free, single-file trip cost planner for **Sarawak, Malaysia**, the Land of the Hornbill. Pick where you're flying from, your Sarawak destination, your dates and your travel style. It estimates the **whole trip**: flights, accommodation with Malaysian taxes, and daily spending. It also shows the weather forecast and converts the total into your currency.

No sign-up. No API keys. No backend.

---

## ✨ Features

| Feature | Details |
| --- | --- |
| **Live recalculation** | Every change updates the total instantly. There's no "calculate" button to press. |
| **Return or one-way** | Return trips include the flight home (v1 counted only one way). |
| **Pick your airline & platform** | Click any airline or hotel platform to use it in the total. The cheapest is pre-selected. |
| **Malaysian hotel taxes** | 10% service charge + 8% SST (estimated). Optional RM10/room/night tourism tax for non-Malaysian guests. |
| **Daily spending** | Food, local transport and activities sliders, with defaults for each travel style. |
| **Cost breakdown chart** | A donut chart and per-person total in a sticky summary panel. |
| **Destination explorer** | Six destination cards with highlights, local food and a live "flights from" price. |
| **Weather** | A day-by-day forecast from Open-Meteo, or a seasonal guide for trips beyond 16 days. |
| **Currency** | Converts the total into USD, SGD, EUR, GBP, AUD, CNY or JPY (ECB rates via Frankfurter). |
| **Share, copy & print** | Share a link that reopens the exact trip, copy a text summary, or print/save as PDF. |
| **Auto-save** | Your last trip is remembered in your browser. |
| **Room advice** | Suggests more rooms when there are more than about 3 guests per room. |
| **Connection warnings** | Flags routes that usually need a stop (Limbang, Mukah, Kota Bharu). |
| **Mobile-first** | Works down to 360px wide, with a sticky total bar on phones. |

---

## 🗺️ Destinations

| From | To (Sarawak) |
|------|-------------|
| Kuala Lumpur (KUL) | Kuching (KCH) |
| Johor Bahru (JHB) | Miri (MYY) |
| Penang (PEN) | Sibu (SBW) |
| Kota Bharu (KBR) | Bintulu (BTU) |
| Kota Kinabalu (BKI) | Limbang (LMN) |
| Labuan (LBU) | Mukah (MKM) |

---

## 💰 Travel Styles

| Style | Flights | Stay | Daily spend default (per person) |
|-------|---------|------|------|
| 🌿 Optimal Budget | Saver fares | Guesthouses & budget hotels | RM 90 / day |
| ✈️ Comfort Travel | Flexi fares | 3–4★ hotels | RM 200 / day |
| 👑 Comfort+ Travel | Premium fares | 5★ stays | RM 450 / day |

---

## 🚀 Run It

Open `index.html` in any browser, or host it free on GitHub Pages, Netlify or Cloudflare Pages.

```bash
git clone https://github.com/Trulypureman/sarawakgo.git
cd sarawakgo
open index.html
```

---

## ⚠️ Disclaimer

Flight fares, hotel rates and daily spending are **reference estimates based on 2026 average market rates, not live prices**. Only the weather (Open-Meteo) and exchange rates (Frankfurter) are fetched live. Always verify the final price with the airline or booking platform before paying. SarawakGo is not affiliated with any airline or booking platform.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| App | One `index.html`: HTML5, CSS3, vanilla JavaScript |
| Fonts | Google Fonts: Playfair Display, Outfit |
| Weather | [Open-Meteo](https://open-meteo.com), free, no key |
| Currency | [Frankfurter](https://frankfurter.dev), free, no key |
| Dependencies | None |

---

## 🤝 Contributing

Pull requests are welcome, for example: more destinations (Mulu, Kapit, Bario), updated price data, AirBorneo/MASwings rural routes, or a Bahasa Malaysia translation.

---

## 📄 License

MIT License: free to use, modify and distribute with attribution.

---

<div align="center">

Made with ❤️ for **Sarawak**, *Land of the Hornbill*

</div>
