# 🚀 PRODIGY_WD_01

A clean, high-performance navigation menu that breathes life into your landing page. This project demonstrates how to handle scroll-state transitions using vanilla web technologies.

---

### ✨ Key Features

* **🖱️ Scroll Sensing**
  The menu "wakes up" and transitions from transparent to solid once you scroll down more than 50 pixels.
* **❄️ Glassmorphism**
  When active, the background uses `backdrop-filter` to blur the content behind it for a frosted-glass effect.
* **✨ Smart Hover**
  Menu links feature a sleek, animated underline that expands from the center on hover.
* **📱 Mobile Ready**
  The layout is fully fluid and automatically adjusts for smartphones and tablets.

---

### 🛠️ Technical Breakdown

The system relies on a lightweight "Observer" logic:

| Component | Responsibility |
| :--- | :--- |
| **HTML5** | Defines the fixed nav structure and navigation list. |
| **CSS3** | Handles the dark-slate theme and the `.scrolled` transition state. |
| **JavaScript** | Listens to the `window.onscroll` event to toggle the UI state. |


---

### 🎨 Design Palette

* **Primary Background:** `#0f172a` (Dark Slate)
* **Accent Color:** `#00ff88` (Neon Green)
* **Typography:** Poppins / System Sans-Serif

---

### 🏁 Getting Started

1. **Clone or Copy:** Save the source code as `index.html`.
2. **Launch:** Open the file in any modern web browser.
3. **Test:** Scroll down the page to trigger the **Navbar Transformation**.
