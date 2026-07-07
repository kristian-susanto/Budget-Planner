# 💍 Wedding Budget Planner: Real-Time Allocation & Management

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-1.3.0-pink)

**Planning your big day shouldn't be a financial headache.** `Wedding Budget Planner` is a lightweight, high-precision client-side tool designed to help couples manage, allocate, and track their wedding expenses dynamically. Input your total budget and instantly see your funds distributed across highly customizable categories and nested sub-items.

---

## 🌟 Key Features

### 📊 Dynamic Cost Allocation Engine

Forget rigid spreadsheets. As soon as you type your budget, the planner instantly distributes funds across various key verticals based on real-time percentage values. It features a live calculation loop using the following simple allocation formula:

$$Nominal\ Estimate = \frac{\text{Category Percentage}}{100} \times \text{Total Budget}$$

### 🏗️ Fully Customizable Architecture

- **Live Category Control:** Directly edit category names or change percentage weights. The nominal estimates update instantly as you type.
- **Granular Sublists:** Add infinite sub-items (e.g., specific vendors, rentals, or tasks) inside major categories to keep fine details perfectly organized.
- **Global Controls:** Seamlessly create brand-new custom spending categories or wipe out existing ones using the inline deletion tools.

### 🛡️ Smart Allocation Validation

The interface includes a real-time validation guard at the bottom of the breakdown table. It automatically calculates the sum of all your categories and gives you instant visual feedback:

- **Perfect Balance:** Displays a solid green checkmark once your distribution hits exactly **100.00%**.
- **Imbalance Warning:** Warns you with an amber indicator showing exactly how much percentage remains or exceeds the limit.

### 🎨 Premium User Experience

- **Dual Theme Toggle:** Instantly switch between light mode and dark mode via the dedicated floating theme switch button.
- **Elegant Feedback UI:** Integrated with **SweetAlert2** to deliver non-intrusive, gorgeous toast alerts for any system action (additions, deletions, warnings).
- **Privacy First:** 100% client-side. No servers, no cookies, no tracking. Your data stays completely safe on your own device.

---

## 🛠️ Technical Stack

- **Markup & Structure:** HTML5 with semantic table components.
- **Styling & Themes:** Vanilla CSS3 utilizing native CSS Custom Variables (`:root` / `[data-theme="dark"]`) for smooth rendering and absolute responsiveness across mobile devices.
- **Logic Engine:** Vanilla JavaScript (ES6+) for instant DOM mutation and reactive calculation loops.
- **External Dependencies:** SweetAlert2 library loaded securely via CDN for premium system notifications.

---

## 🚀 Quick Start

1. **Download** the `index.html` file.
2. **Open** it in any modern web browser (Chrome, Safari, Firefox, Edge).
3. **Plan.** Type in your total budget amount, adjust your percentage slices, and start designing your dream wedding budget instantly.

---

## 📂 Project Structure

```text
├── index.html        # Single-file Application (HTML, CSS Variables, & JS Logic)
└── README.md         # Documentation
```

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

_Created with ❤️ for couples planning their forever._
