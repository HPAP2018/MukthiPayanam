# MukthiPayanam — Journey to the 108 Divya Desams

An interactive web map of the **108 Divya Desams** — the sacred Vishnu temples revered by the Alvar saints in the Naalayira Divya Prabandham.

**🌐 Live map:** https://YOUR-USERNAME.github.io/MukthiPayanam/

## What is this?

The 108 Divya Desams are a set of Vaishnavite shrines sung by the twelve Alvar saint-poets between the 6th and 9th centuries CE. **106 are located on Earth** across India and Nepal; the remaining two — *Tirupparkatal* (Kshira Sagara, the cosmic ocean of milk) and *Tirupparamapadam* (Vaikuntha, the eternal abode) — are celestial and not plotted here.

This map plots all 106 earthly temples on an interactive world map, color-coded by region.

## Features

- 🗺️ All 106 earthly Divya Desams plotted on OpenStreetMap
- 🎨 Color-coded markers by region (Tamil Nadu, Kerala, Andhra Pradesh, Uttar Pradesh, Uttarakhand, Gujarat, Nepal)
- 🔍 Search by temple name or place
- 🏷️ Filter by region
- 📋 Scrollable sidebar list — click any temple to fly there
- ℹ️ Detailed popup for each temple showing the presiding **Perumal** (Vishnu form) and **Thayar** (consort)
- 🏠 Reset button to return to the full South Asia view

## Region distribution

| Region | Temples |
|---|---|
| Tamil Nadu | 84 |
| Kerala | 11 |
| Uttar Pradesh | 4 |
| Uttarakhand | 3 |
| Andhra Pradesh | 2 |
| Nepal | 1 |
| Gujarat | 1 |

## Tech

A single-file static webpage — pure HTML/CSS/JavaScript with [Leaflet.js](https://leafletjs.com/) and OpenStreetMap tiles. No build step, no dependencies to install. Just open `index.html` in any browser.

## Running locally

```bash
# Option 1: Just open the file
open index.html

# Option 2: Serve it (so URLs work cleanly)
python -m http.server 3000
# then visit http://localhost:3000
```

## Credits

- Temple data sourced from public references on the 108 Divya Desams
- Map tiles © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors
- Map library: [Leaflet.js](https://leafletjs.com/)

## License

MIT — feel free to fork, modify, and share.
