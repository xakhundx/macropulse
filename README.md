# 🥗 MacroPulse — Macro Cost-Per-Gram & Meal Prep Optimizer

> **Microeconomic Grocery Efficiency Engine for Fitness & Bodybuilding**  
> *Zero external API keys • Zero login walls • 100% Client-Side LocalStorage Persistence*

Built by **[Ammar Akhund](https://xakhundx.github.io/Portfolio/)** (Economics Major & Statistics Minor, University of Manitoba `'27` · [@akhund_fit](https://www.instagram.com/akhund_fit/)).

---

## 🎯 Executive Overview & Purpose

**MacroPulse** solves a fundamental financial dilemma faced by athletes and gym-goers:
> *"How do you reliably hit 150g–220g+ of daily protein without blowing \$150–\$200/week on expensive grocery cuts and dining out?"*

Combining microeconomic consumer choice theory with sports nutrition, MacroPulse treats daily meal prep as a constrained optimization problem:
$$\max_{\mathbf{x}} \sum_{i=1}^n x_i \cdot \text{Protein}_i \quad \text{subject to} \quad \sum_{i=1}^n x_i \cdot \text{Price}_i \le \text{Budget}_{\text{weekly}} \quad \text{and} \quad \sum_{i=1}^n x_i \cdot \text{Calories}_i \le \text{Calories}_{\text{target}}$$

---

## 🔬 Core Economic & Nutritional Metrics

- **Protein Yield per Dollar ($g/\$$):**
  $$\text{Yield} = \frac{\text{Total Grams Protein in Package}}{\text{Total Package Price CAD}}$$
  Ranks grocery staples from Elite Efficiency ($>20\text{g}/\$$) to Luxury ($<8\text{g}/\$$).
- **Standardized Cost per 25g Serving:**
  $$\text{Cost}_{25g} = \left(\frac{\text{Price}}{\text{Total Protein}}\right) \times 25$$
- **Pareto Efficiency Frontier:** Identifies substitution opportunities (e.g. replacing lean beef with liquid egg whites and Greek yogurt to save \$21.40/week with zero macro drop).
- **Fast-Casual Baseline Comparison:** Calculates weekly savings against eating out / takeout bowls (\$28/day benchmark).

---

## 🛠️ Architecture & Tech Stack

- **UI & Layout:** Tailwind CSS (v3.4), custom obsidian glassmorphic styling, JetBrains Mono telemetry.
- **Data Visualization:** Chart.js (v4.4) horizontal efficiency bar chart, dual cost and protein doughnut breakdowns.
- **Persistence:** Real-time synchronization to browser `localStorage`.
- **Social Engine:** 1-Click **`@akhund_fit` & LinkedIn Post Generator** formatted with verified grocery numbers, percentages, and hashtags.

---

## 🚀 Running Locally or Deploying to GitHub Pages

### Run Locally
Open `index.html` directly in any web browser.

### Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "feat: initial release of MacroPulse meal prep optimizer"
git branch -M main
git remote add origin https://github.com/xakhundx/macropulse.git
git push -u origin main
```
Then navigate to **Repository Settings → Pages → Deploy from branch (main)**.
