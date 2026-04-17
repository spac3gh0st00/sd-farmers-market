# 🌿 SD Farmers Market

> **A beautiful, community-first guide to every farmers market in San Diego County.**

🔗 **Live Site →[Fresh From the Farm
to Your Table](https://spac3gh0st00.github.io/sd-farmers-market/)**

---

## ✨ Features

- 🗺️ **Interactive Map** — Free OpenStreetMap/Leaflet embed, no API key required
- 📍 **Find Nearest Market** — Uses your geolocation to highlight the closest market and fly the map to it
- ✅ **Open Now Badges** — Green indicators on cards and map pins for currently-open markets based on live time
- 🔍 **Search & Filter** — Filter by day-of-week pills (including a smart "Today" button) or search by name/neighborhood
- 🃏 **Market Cards** — Click any card to fly the map to that market and open its info popup
- 📱 **Fully Responsive** — Works great on mobile, tablet, and desktop
- 🍅 **20 Markets** — Comprehensive coverage across San Diego County: Little Italy, Hillcrest, OB, PB, La Jolla, Encinitas, Del Mar, Carlsbad, and more

---

## 🏪 Markets Included

| Market | Neighborhood | Day | Hours |
|--------|-------------|-----|-------|
| Little Italy Mercato | Little Italy | Saturday | 8:00 AM – 2:00 PM |
| Hillcrest Farmers Market | Hillcrest | Sunday | 8:00 AM – 2:00 PM |
| Ocean Beach Farmers Market | Ocean Beach | Wednesday | 4:00 PM – 8:00 PM |
| Pacific Beach Tuesday Market | Pacific Beach | Tuesday | 2:00 PM – 7:00 PM |
| North Park Thursday Market | North Park | Thursday | 3:00 PM – 7:00 PM |
| South Park Sunday Market | South Park | Sunday | 9:00 AM – 2:00 PM |
| La Jolla Open Aire Market | La Jolla | Sunday | 9:00 AM – 1:00 PM |
| Coronado Certified FM | Coronado | Tuesday | 2:30 PM – 6:00 PM |
| Encinitas Certified FM | Encinitas | Saturday | 9:00 AM – 1:00 PM |
| Del Mar Certified FM | Del Mar | Saturday | 1:00 PM – 4:00 PM |
| Carlsbad Village FM | Carlsbad | Wednesday | 2:30 PM – 6:00 PM |
| Rancho Santa Fe FM | Rancho Santa Fe | Friday | 9:00 AM – 1:30 PM |
| Poway Farmers Market | Poway | Saturday | 8:00 AM – Noon |
| Vista Farmers Market | Vista | Saturday | 8:00 AM – Noon |
| Escondido Certified FM | Escondido | Tuesday | 2:30 PM – 6:00 PM |
| Mission Valley FM | Mission Valley | Wednesday | 9:00 AM – 1:00 PM |
| Mira Mesa Sunday Market | Mira Mesa | Sunday | 8:00 AM – 11:00 AM |
| Chula Vista FM | Chula Vista | Thursday | 4:00 PM – 8:00 PM |
| National City Thursday Market | National City | Thursday | 1:00 PM – 5:00 PM |
| Santee Farmers Market | Santee | Tuesday | 3:00 PM – 7:00 PM |

---

## 🛠️ Tech Stack

- **Pure HTML/CSS/JS** — zero build tools, zero dependencies to install
- **[Leaflet.js](https://leafletjs.com/)** — open-source interactive maps
- **[OpenStreetMap](https://www.openstreetmap.org/)** — free map tiles, no API key needed
- **[Google Fonts](https://fonts.google.com/)** — Playfair Display + DM Sans
- **GitHub Pages** — free static hosting

---

## 🚀 Running Locally

No build step required — just open the file:

```bash
git clone https://github.com/spac3gh0st00/sd-farmers-market.git
cd sd-farmers-market
open index.html   # macOS
# or just drag index.html into your browser
```

---

## 🤝 Contributing

Know a market that's missing? Hours changed? PRs welcome!

1. Fork the repo
2. Add or update the market entry in the `MARKETS` array inside `index.html`
3. Open a pull request

Each market entry follows this shape:

```js
{
  name: "Market Name",
  location: "Full Address, City",
  day: "Saturday",          // Day of week
  time: "8:00 AM – 1:00 PM",
  start: 8,                 // 24hr decimal (e.g. 8.5 = 8:30 AM)
  end: 13,
  lat: 32.000,
  lng: -117.000,
  emoji: "🌿"               // Flavor emoji for the card
}
```

---

## 📋 Roadmap

- [ ] Add seasonal market events and special vendors
- [ ] Filter by market type (certified organic, specialty, etc.)
- [ ] Add market website / social links to cards
- [ ] Dark mode

---

*Hours may vary — always check with the market directly before visiting.*  
*Built with 🌿 for San Diego food lovers.*
