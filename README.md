# VaultAI: Prescriptive Student Financial Manager 🚀

**VaultAI** is a high-fidelity, client-side financial intelligence tool designed for the 2026 student ecosystem. It moves beyond simple expense tracking into **Prescriptive Analytics**, telling students not just where their money went, but what specific lifestyle changes will help them reach their goals.

---

## 🧠 The Logic Engine (The Math)

The core of VaultAI is built on a custom financial model tailored for Indian university life:

### 1. The Total Expense Formula
The system calculates monthly outflow ($E_{total}$) using the following variables:
$$E_{total} = F_{fixed} + (O_{food} \times 250) + T_{mode} + B_{exam}$$

* **$F_{fixed}$**: Set at ₹6,000 (Covers basic mess fees, utilities, and room rent).
* **$O_{food}$**: Number of external Swiggy/Zomato orders (Average cost pegged at ₹250/order).
* **$T_{mode}$**: Commute cost based on mode (Walking: ₹0, Public: ₹1,200, Cab: ₹4,000).
* **$B_{exam}$**: Dynamic buffer of ₹1,500 applied only during "Exam Season" for snacks/caffeine.

### 2. The Savings & Goal Projection
The "Time to Goal" ($T$) is calculated as:
$$T = \frac{G_{target}}{Allowance - E_{total}}$$
Where $G_{target}$ is the user's custom savings goal (e.g., a New Smartphone).

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (for the Glassmorphic UI).
* **Visualizations:** Chart.js (Real-time Donut and Bar charts).
* **Security:** HTML5 LocalStorage for session persistence and Gatekeeper authentication.
* **Design System:** Glassmorphism (High-blur backdrops, 0.1 opacity borders, neon accents).

---

## 🌟 Key Features

1.  **Gatekeeper Auth:** A secure landing page entry system using University ID credentials.
2.  **AI Action Plan:** A dynamic text engine that generates human-readable advice based on budget deficits.
3.  **Real-Time Simulation:** Change a slider (like food frequency) and see the "Goal Progress" percentage update instantly.
4.  **Financial Health Indicators:** Visual cues (Green/Red) that trigger when savings fall below 15% of the total allowance.

---

## 🚀 Quick Start

1.  Clone or download the project folder.
2.  Ensure `index.html` and `dashboard.html` are in the same directory.
3.  Open `index.html` in any modern web browser (Chrome/Edge/Brave).
4.  **Login Credentials:**
    * **ID:** `STU-2026`
    * **Key:** `vault123`

---

## 📈 Future Roadmap

* **v2.0:** Integration with UPI SMS parsing for automatic expense logging.
* **v3.0:** "Group Vaults" for shared flat expenses and split-bill logic.
* **v4.0:** Dark-mode optimized PDF reports for monthly financial reviews.