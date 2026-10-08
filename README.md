# 💰 Budget Planner: Real-Time Allocation & Management

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-2.0.0-indigo)

**Take control of your money without the spreadsheet hassle.**  
`Budget Planner` is a lightweight, high‑precision client‑side tool that helps you allocate, track, and visualise any budget in real time. Simply enter your total budget and watch it distribute instantly across fully customisable categories and nested sub‑items.

---

## 🌟 Key Features

### 📊 Dynamic Cost Allocation Engine
Forget rigid spreadsheets. As soon as you type your budget, the planner instantly distributes funds across categories based on real‑time percentage values. The live calculation uses this simple formula:

$$Nominal\ Estimate = \frac{\text{Category Percentage}}{100} \times \text{Total Budget}$$

### 🏗️ Fully Customisable Architecture
- **Live Category Control:** Edit category names or change percentage weights directly in the table. Nominal estimates update instantly.
- **Granular Sub‑items:** Add unlimited sub‑items inside any category to keep fine details organised.
- **Global Controls:** Create brand‑new custom categories or delete existing ones with inline tools.
- **Smart Percentage Step:** The up/down arrows on percentage inputs adjust by **0.5** for quick, intuitive fine‑tuning.

### 🛡️ Smart Allocation Validation
A live status indicator at the bottom of the breakdown table gives instant feedback:
- **Perfect Balance:** A green checkmark appears when your distribution totals exactly **100.00%**.
- **Imbalance Warning:** An amber warning shows how much percentage remains or exceeds the limit.

### 📤 Multi‑Format Export
Download your budget plan in **7 different formats**, each generated from a clean, professional snapshot (no input placeholders, no add‑forms, no buttons):
- **CSV** – comma‑separated values for spreadsheets.
- **XLSX** – native Excel workbook.
- **JSON** – structured data for developers.
- **PNG** – high‑resolution raster image.
- **JPG** – compressed raster image.
- **PDF** – print‑ready A4 document with pagination.
- **SVG** – scalable vector graphic for infinite zoom.

All exports use a **light theme** regardless of your current UI theme, and include a subtle footer with the generation date.

### 🎨 Premium User Experience
- **Dual Theme Toggle:** Switch between light and dark mode with the floating moon/sun button.
- **Elegant Feedback:** Integrated with **SweetAlert2** for non‑intrusive toast alerts on every action (add, delete, warning, export success).
- **Privacy First:** 100% client‑side. No servers, no cookies, no tracking. Your data never leaves your device.

---

## 🛠️ Technical Stack

- **Markup & Structure:** HTML5 with semantic table components.
- **Styling & Themes:** Vanilla CSS3 using native CSS Custom Variables (`:root` / `[data-theme="dark"]`) for smooth theming and full responsiveness.
- **Logic Engine:** Vanilla JavaScript (ES6+) for instant DOM updates and reactive calculations.
- **Export Libraries (CDN):**
  - [SheetJS (xlsx)](https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js) – Excel export.
  - [html2canvas](https://cdn.jsdelivr.net/npm/html2canvas@1.4.1/dist/html2canvas.min.js) – PNG/JPG/PDF rendering.
  - [jsPDF](https://cdn.jsdelivr.net/npm/jspdf@2.5.1/dist/jspdf.umd.min.js) – PDF generation.
  - [dom-to-image](https://cdn.jsdelivr.net/npm/dom-to-image@2.6.0/dist/dom-to-image.min.js) – SVG export.
  - [SweetAlert2](https://cdn.jsdelivr.net/npm/sweetalert2@11) – toast notifications.

---

## 🚀 Quick Start

1. **Download** the `index.html` file.
2. **Open** it in any modern browser (Chrome, Safari, Firefox, Edge).
3. **Plan.** Enter your total budget, adjust the percentage sliders, add or remove categories, and export your plan in your preferred format.

No installation, no build step, no dependencies to install.

---

## 📂 Project Structure

```text
├── index.html        # Single-file application (HTML, CSS variables, & JS logic)
└── README.md         # Documentation
```

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

_Created with ❤️ for couples planning their forever._
