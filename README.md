# Movie Genre Trends and Ratings Analysis (2005–2025)

This project explores how movie genres have evolved over the past 20 years based on IMDb data. It aims to uncover patterns in genre popularity, audience engagement, and movie ratings.

## Objectives

- Identify genres with the highest average ratings
- Analyze shifts in genre popularity over time
- Examine audience engagement through number of votes
- Observe rating trends across years
- Showcase top-rated movies within the most popular genres

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

The dataset was originally available on Kaggle (now unavailable). A local version was preserved for this analysis. It includes:

- `title`, `type`, `genres`, `averageRating`, `numVotes`, `releaseYear`, etc.
- Only movies (`type == "movie"`) from **2005 to 2025** were analyzed.

## Key Findings

- **Highest-rated genres**: Documentary, Animation, Mystery
- **Most produced genres**: Drama, Action
- **Rising/Falling trends**:
  - Biography rose until 2018 then declined
  - Comedy and Crime have been steadily declining
- **Most audience engagement**: Sci-Fi, Horror, Adventure (by vote count)
- **Ratings trend**: Fairly stable average ratings year-over-year
- **Top 3 movies per genre**: Identified based on rating within each top genre

## Visual Summary

The full set of charts is available in the [presentation PDF](./Movie%20Genre%20Trends%20and%20Ratings%20Analysis%20.pdf).

## How to Run

1. Clone the repo
2. Ensure `data.csv` is in the root directory
3. Run the notebook:
   ```bash
   jupyter notebook movie-genre-analysis-project.ipynb
