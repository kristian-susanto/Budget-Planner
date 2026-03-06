# 🕊️ Wedding Planner: Smart Inflation-Adjusted Budgeting

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-1.2.0-pink)

**Planning a wedding shouldn't be a financial mystery.** `Wedding Planner` is a high-precision budgeting tool that bridges the gap between your current lifestyle and your dream celebration. By leveraging historical inflation data, it transforms your monthly spending power into a realistic, future-proof wedding budget.

---

## 🌟 Key Pillars

### 📈 Smart Inflation Engine

Traditional calculators use fixed multipliers. Our engine uses a **Compound Annual Growth Rate (CAGR)** model based on 40+ years of historical inflation data to ensure your budget stays realistic against rising costs.

### 🎨 Bespoke Planning Levels

- **Charming & Intimate:** Focused on essential elegance.
- **Classic Elegance:** A refined hotel or outdoor experience.
- **Grand Luxury:** A lavish gala calculated with a 15-year inflation-adjusted horizon.

---

## 🛠️ Technical Implementation

### The Core Algorithm

The "Grand Luxury" tier uses an accumulative compounding logic to reach high-tier targets (e.g., transforming a ~5.4M input into a ~1.3B target):

$$Budget = \sum_{t=1}^{n} (Monthly \times 12) \times (1 + r)^t$$

_Where:_

- $n = 15$ years (for Premium)
- $r = \text{calculated historical average inflation}$

### Interactive Features

- **Real-time Allocation:** Drag and drop percentages for Venue, Catering, and Decor.
- **Dynamic UI:** Seamlessly switch between **Obsidian Dark** and **Soft Porcelain** themes.
- **Mobile First:** Fully responsive table layouts for planning on the go.

---

## 🚀 Quick Start

1. **Download** the `index.html` file.
2. **Open** it in any browser (Chrome, Safari, Edge).
3. **Plan.** No servers, no data tracking, 100% private.

---

## 📂 Project Structure

```text
├── index.html        # Main Application & Logic
├── README.md         # Documentation
└── assets/           # (Optional) Images & Icons
```

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

_Created with ❤️ for couples planning their forever._
