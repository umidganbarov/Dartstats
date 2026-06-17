# Dartstats 🎯

A simulation-based data analysis project built to get hands-on with Python's core data science stack — NumPy, Pandas, and Matplotlib.

## What it does

Loads a CSV of dart throw coordinates for 3 players and lets you explore the data through a terminal menu. You can visualize each player's hits as scatter plots, compare all three at once, see a stacked bar chart of score distributions, and run a full analysis that prints scores, average displacement from center, and declares a winner.

## Files

| File | Description |
|------|-------------|
| `engine.py` | Main script — all logic, plots, and menu |
| `data.csv` | Raw dart hit coordinates (x, y) per throw |

## How to run

```bash
pip install pandas numpy matplotlib
python engine.py
```

## Stack

- **Pandas** — CSV loading and player-row slicing
- **NumPy** — Array operations for plotting
- **Matplotlib** — Scatter plots and stacked bar charts

## Learning focus

The goal was practical fluency: reading real data, slicing it by player, computing stats, and building multiple chart types from scratch. No templates, just the docs and experimentation.

## Resources

- [Matplotlib docs](https://matplotlib.org)
- [YouTube — Matplotlib tutorials](https://www.youtube.com)
