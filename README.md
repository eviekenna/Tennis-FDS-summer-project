# 🎾 Tennis-FDS-Summer-Project

This project explores data-driven methods for **re-ranking players in tennis tournaments** based on performance metrics rather than traditional seedings. The goal is to analyze whether performance-based reseeding can improve predictive accuracy in later rounds of Grand Slam events.

## 📂 Project Structure
- `notebooks/`: Contains Jupyter notebooks with exploratory analysis and modeling
- `data/`: Raw and processed datasets (excluded in this repo if large or private)
- `src/`: Python scripts for data processing and modeling

## 📊 Current Focus
- Collecting and cleaning match data from Grand Slam tournaments (2015–2023)
- Building models to re-rank players after Round 1 based on:
  - Match duration (e.g., 3 sets vs. 5 sets)
  - Rank differential
  - Other performance metrics

## 💻 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/eviekenna/Tennis-FDS-summer-project.git
