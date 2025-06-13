# hr-graph

A visual exploration of the HR tech ecosystem using interactive D3.js graphs.

This project helps people understand the complexity and interdependencies within modern HR technology — through radial trees, partition diagrams, and more. It aims to provide a clear, visual map of how different HR modules connect and evolve in the broader ecosystem.

---

## 🧠 Motivation

HR tech is often seen as fragmented and hard to navigate. By visualizing it, we want to:

- Help founders, operators, and developers understand the landscape
- Spark conversations around interoperability and modularity
- Make learning and exploring HR domains more interactive

---

## 📦 What's Inside

- `index.html`: Simple HTML file rendering charts with D3.js
- Two interactive visualizations:
  - **Partition Chart** – shows module breakdown and size distribution
  - **Radial Tree** – shows hierarchical structure and interdependencies

Each visualization supports zooming, navigation, and is built with pure D3.js (no build tools required).

---

## 🚀 Getting Started

Clone this repository and open `index.html` in your browser:

```bash
git clone https://github.com/yourusername/hr-graph.git
cd hr-graph
open index.html
```

## 🛠️ TODO

- [ ] Enhance data by creating a dedicated `.md` file for each HR category/module
- [ ] Add clickable links to nodes that open the relevant `.md` file in a new tab
- [ ] Enable filtering or highlighting specific domains (e.g. Payroll, Talent)
- [ ] Make the layout responsive for smaller screens
- [ ] Export visualizations as PNG or PDF
- [ ] Host the chart with GitHub Pages or Netlify for public access
