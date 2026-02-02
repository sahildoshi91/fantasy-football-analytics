# fantasy-football-analytics
Learning GitHub + Python for fantasy football analytics

# 🏈 2026 Dynasty Scout: Play-Caller & Efficiency Analysis

A data-driven scouting tool designed to identify high-upside Dynasty fantasy football targets by blending advanced efficiency metrics (EPA) with 2026 coaching and play-calling shifts.

## 🚀 Overview
This project analyzes NFL play-by-play data to categorize players into four actionable tiers. By overlaying offensive system changes, we can predict breakouts before they happen in the 2026 season.

## 📊 Key Features
- **Efficiency Mapping:** Uses Expected Points Added (EPA) per play to measure player impact.
- **Play-Caller Logic:** Integrates a custom 2026 coaching map (e.g., Mike McDaniel to LAC, Brian Daboll to TEN).
- **Dynasty Tiers:**
  - **Tier 1 (Unicorns):** Elite volume and elite efficiency.
  - **Tier 2 (Hidden Gems):** High efficiency on low volume — prime trade targets.
  - **Tier 3 (Volume Traps):** High volume but low efficiency — sell-high candidates.

## 🛠️ Tech Stack
- **Python:** Data processing and analysis.
- **nflreadpy:** For fast access to nflverse play-by-play and roster data.
- **Plotly Express:** Interactive scatter plots for visualization.
- **Pandas:** Advanced data manipulation and tiering.

## 📈 Visualization
The interactive dashboard allows for filtering by position (WR/RB/TE) and age, helping you find the youngest "Hidden Gems" in the league.

## 📥 Installation
To run this analysis locally, you will need Python 3.10+ and the following libraries:
```bash
pip install nflreadpy pandas plotly nbformat
