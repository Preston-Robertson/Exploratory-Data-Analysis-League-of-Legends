# Exploratory Data Analysis: League-of-Legends ⚔️

A data analysis project examining champion balance in *League of Legends*. Using real match and champion statistics data, this project applies exploratory data analysis (EDA) and visualization techniques to investigate whether the game's 150+ champion roster is balanced — and where it might not be.

---

## Motivation

*League of Legends* is one of the most-played games in the world, with a roster of over 150 unique champions. Maintaining balance across all of them is one of Riot Games' greatest ongoing challenges. This project uses data analysis to:

- Quantify balance (or imbalance) across champions, roles, and stat categories
- Identify outliers — champions that may be over- or under-powered relative to their peers
- Demonstrate the power of data analysis on a large, complex, real-world dataset

---

## Project Structure

```
Project-League-of-Legends/
├── Code/               # Jupyter notebooks with analysis and visualizations
├── Data/               # Raw and processed datasets
├── Documents/          # Supporting write-ups and findings
├── Images/             # Charts, plots, and visual outputs
└── README.md           # This file
```

---

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or JupyterLab

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Preston-Robertson/Project-League-of-Legends.git
cd Project-League-of-Legends
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

Core libraries used in this project include `pandas`, `numpy`, `matplotlib`, and `seaborn`.

**3. Launch Jupyter**

```bash
jupyter notebook
```

Then open the notebooks in the `Code/` folder to explore the analysis.

---

## About the Data

The dataset(s) in the `Data/` folder contain champion-level and/or match-level statistics from *League of Legends*, potentially including:

| Feature Category | Examples |
|-----------------|---------|
| Champion stats | Win rate, pick rate, ban rate, KDA |
| Role/position | Top, Jungle, Mid, ADC, Support |
| Base stats | Health, mana, armor, attack damage |
| Match outcomes | Kills, deaths, assists, gold earned |

Data may be sourced from publicly available datasets on platforms such as [Kaggle](https://www.kaggle.com/search?q=league+of+legends) or from Riot Games' official API.

---

## Analysis Overview

The notebooks in `Code/` walk through the full data analysis pipeline:

**1. Data Loading & Cleaning**
- Importing and inspecting the raw dataset
- Handling missing values, type casting, and normalization

**2. Exploratory Data Analysis (EDA)**
- Distributions of win rates, pick rates, and ban rates across champions
- Role-by-role comparisons to assess positional balance
- Correlation analysis between champion stats and performance metrics

**3. Balance Analysis**
- Identifying statistical outliers — champions with unusually high or low win/pick/ban rates
- Examining whether certain roles or classes of champions are systematically stronger
- Visualizing the spread of performance metrics across the roster

**4. Visualizations**
- Bar charts, heatmaps, scatter plots, and box plots generated with `matplotlib` and `seaborn`
- All figures are saved in the `Images/` folder

---

## Key Questions Explored

- Which champions have the highest and lowest win rates?
- Is there a correlation between pick rate and win rate?
- Are certain roles (e.g. Jungle, Support) systematically over- or under-tuned?
- What champion stats most strongly predict in-game performance?

---

## Tools & Libraries

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Plotting and visualization |
| `seaborn` | Statistical data visualization |
| `jupyter` | Interactive notebook environment |

---

*League of Legends is a registered trademark of Riot Games. This project is an independent data analysis and is not affiliated with or endorsed by Riot Games.*
