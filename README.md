# 🌍 Global Terrorism Analysis Dashboard

This project analyzes worldwide terrorist incidents using the [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd/). The goal is to draw meaningful insights from the data and visualize it through charts and maps.

---

## 📊 Key Insights

- 📈 **Terrorist incidents over time**: Clear increase in incidents during certain years, with regional variations.
- ⚰️ **Casualties vs. Incidents**: Generally correlated, but several outliers exist (e.g., highly deadly events).
- 🔫 **Common attack types**: Bombings and armed assaults are most frequent.
- 🌍 **Regional spread**: Dense clusters in South Asia, Middle East & North Africa.

---

## 🛠️ Tech Stack

- **Python**
  - `pandas` – Data manipulation
  - `matplotlib`, `seaborn` – Charts
  - `folium` – Interactive maps
- **Jupyter Notebook / VS Code**
- **Git & GitHub** – Version control and publishing

---

## 📁 Files Included

| File Name                | Description                                  |
|-------------------------|----------------------------------------------|
| `terror_map.html`       | Interactive Folium map of global incidents    |
| `clean.ipynb`        | Python notebook with full analysis           |
| `README.md`             | Project documentation                        |

---
## 🗺️ Map of Global Terrorist Incidents

An interactive map was created using the [Folium](https://python-visualization.github.io/folium/) library to visualize over 180,000+ global terrorist incidents.

📍 Each red dot represents a recorded terrorist attack.

![Global Terrorism Map](terorrism_map.png)


## 📍 How to View the Map

Open the `terror_map.html` file in your browser:

```bash
open terror_map.html
