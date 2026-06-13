# FIA Twilight Character Analysis

**Female Intelligence Agency (FIA) — Twilight (2008) Behavioral Analysis**
GMU Capstone Project — 3A Synergy Team

🔗 **Live Website:** https://fia-twilight.vercel.app

---

## What This Project Does

This project applies the **Female Intelligence Agency (FIA) methodology** to analyze characters in the Twilight (2008) film. The FIA methodology identifies personality types and behavioral traits in characters based on how they speak and behave.

The pipeline reads character data analyzed across 4 AI platforms (GPT, Copilot, DeepSeek, Gemini), averages the scores, and displays them on a live interactive website.

---

## Key Findings — Edward Cullen

| | |
|---|---|
| **Top Player Type** | Conspiratorial Corey (7.85/10) |
| **Highest Traits** | Goal Persistence (9.33), Unorthodoxy (8.67), Grandiosity (8.0), Intensity (8.0) |
| **Analysis** | Averaged across GPT, Copilot, DeepSeek, and Gemini |

---

## Project Structure

```
fia-twilight/
├── index.html          # The live website (auto-generated)
├── Twilight.xlsx       # FIA analysis data from 4 AI platforms
├── generate_site.py    # Python script that reads Excel and builds the website
└── README.md           # This file
```

---

## How It Works

1. **Data Collection** — The Twilight screenplay was analyzed using 4 AI platforms (GPT, Copilot, DeepSeek, Gemini), each scoring Edward Cullen across 28 FIA trait dimensions and 17 player types
2. **Averaging** — All platform scores are averaged in `Twilight.xlsx`
3. **Website Generation** — `generate_site.py` reads the Excel file and generates `index.html` with interactive charts
4. **Deployment** — The website is hosted on Vercel and auto-updates when code is pushed to GitHub

---

## Running Locally

```bash
# Install dependency
pip3 install openpyxl

# Generate the website
python3 generate_site.py

# Open index.html in your browser
open index.html
```

---

## FIA Methodology

The **Female Intelligence Agency** methodology analyzes characters across:
- **28 bipolar trait dimensions** (scored 0-10, where 5 = healthy)
- **17 player types** (e.g., Manipulative Morgan, Conspiratorial Corey, Charming Charlie)
- **4 analytical frameworks** including good-faith/bad-faith gate and format-baseline calibration

---

## Team

- **Lasya Aravabhumi** — Technical pipeline & website deployment
- **Erik Mieckowski** — Technical pipeline & website deployment  
- **Luul Hawa Shire** — FIA behavioral analysis
- **Cathy** — Multi-platform AI scoring

**Advisor:** Yasser Jaghoori (3A Synergy)  
**Course:** GMU Capstone Project
