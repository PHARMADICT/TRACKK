# PharmaTrack Mobile · Boots T3 Arrivals
### GS1 Scanner · Expiry Tracker · Planogram · KPI
**The Complete Pharmacist — Vysakh Chandran · BOO · 331356**

---

## 📱 4 Pages

| Tab | What it does |
|-----|-------------|
| 🏠 **Home** | Live stats, quick scan, recent scans with expiry colour status |
| 📊 **KPI** | 10-slot hourly sales tracker — tap any slot to enter Sale/TRN/No7/Aura. Exports CSV. |
| 📷 **Scan** | GS1 camera + manual input. Full 5-step Triple-Check engine. Expiry + batch entry. History with search & export. |
| 📦 **Planner** | Full Boots T3 planogram — 160+ real products across Joint & Bone, Omega, Weight Management, Sleep & Relax. Filter by section, search by name/barcode/shelf, tap any product to scan it. |

---

## ⬡ GS1 Triple-Check Engine

1. **GTIN Exact** — 14-digit match  
2. **Normalised GTIN** — leading-zero stripped  
3. **Barcode Fallback** — EAN-13/UPC direct  
4. **RMS Lookup** — Alshaya code match  
5. **Fuzzy 85%** — Levenshtein + Jaccard  

**Expiry colours:** 🔴 Expired · 🟠 < 90 days · 🟢 > 90 days · animated glow on expired cards

---

## 🚀 Deploy — Netlify (60 seconds)

1. Go to **https://app.netlify.com**
2. New site → Deploy manually
3. Drag the **entire `pharmatrack-mobile/` folder** onto the drop zone
4. Live ✓

---

## 🐙 Deploy — GitHub + Netlify

```bash
git init
git add .
git commit -m "PharmaTrack Mobile v1"
git remote add origin https://github.com/YOUR_USERNAME/pharmatrack-mobile.git
git push -u origin main
# In Netlify → Import from Git → publish dir: . → Deploy
```

---

## 📱 Install as PWA

- **iOS Safari** → Share → Add to Home Screen  
- **Android Chrome** → ⋮ → Add to Home Screen  
- **Desktop** → Chrome install icon in address bar

---

## 💾 Storage

All data (KPI, scan history) stored in **localStorage** — private, offline, no server needed.  
Master planogram data is embedded — 160+ real Boots T3 products with barcodes.

---

## 🌓 Night / Light Mode

Tap **🌓** in the top-right header. Preference saved across sessions.  
Dark = iOS deep-navy glass · Light = soft blue-tinted white glass.

---

## 📊 KPI — How to Enter

Tap any time slot row → calculator appears → enter Sale AED, press `=` → prompts for TRN, No7, Aura.  
Totals and ATV/No7%/Aura% computed live.

---

*Built by Vysakh Chandran · The Complete Pharmacist*  
*PharmaTrack Mobile v1.0 · October 2026*
