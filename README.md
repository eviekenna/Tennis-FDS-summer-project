# Tennis-FDS-Summer-Project

This project explores machine learning methods fo re-ranking tennis players in tournaments (mainly focused on grandslams) based on performance in the first round of the tournamnet rather than traditional seedings. The goal is to analyze whether performance-based reseeding can improve predictive accuracy in later rounds of Grand Slam events.

##  Project Structure
- `notebooks/`: Contains Jupyter notebooks with exploratory analysis and modeling
- `data/`: Raw and processed datasets (excluded in this repo if large or private)
- `src/`: Python scripts for data processing and modeling

## Current Focus
- Collecting and cleaning match data from Grand Slam tournaments (2015–2023)
- Building models to re-rank players after Round 1 based on:
  - Fatigue (e.g., 3 sets vs. 5 sets)
  - Match dominance (Games won vs games played)
  - Other engineered performance features

##
 Clone the repo:
   ```bash
   git clone https://github.com/eviekenna/Tennis-FDS-summer-project.git
