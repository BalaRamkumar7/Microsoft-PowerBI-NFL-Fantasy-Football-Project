## Overview
This project analyzes NFL fantasy football performance data across the 2024 and 2025 regular seasons to identify year-over-year trends in player usage, efficiency, and production. Using multi-season fantasy and opportunity metrics, I built an interactive Power BI dashboard to compare player performance across seasons. Rather than producing predictions, the project emphasizes descriptive trend analysis grounded in historical performance.

## Final Project (Main Page)
<img width="1465" height="822" alt="image" src="https://github.com/user-attachments/assets/668a0fdb-80a9-42a7-9c5e-7bb83b45cfd0" />

## Objectives
- Analyze NFL fantasy football performance across the 2024 and 2025 seasons
- Engineer usage and efficiency-based metrics to support year-over-year comparison
- Identify consistent performers, year-over-year breakouts, and regression risks
- Examine how changes in usage and efficiency impact fantasy production
- Create an interactive Power BI dashboard to explore multi-season trends

## Tools
- Power BI for data modeling, DAX measures, and visualization
- CSV-based NFL player datasets (QB, RB, WR)
- Git/GitHub for version control and documentation

## Methodology
- Loaded and cleaned position-specific NFL datasets (QB, RB, WR) for multiple seasons
- Standardized player identifiers to enable cross-season comparisons
- Built a unified player lookup table to support relational modeling
- Created custom DAX measures for PPR fantasy scoring
- Engineered usage and efficiency metrics (targets, rush attempts, fantasy points per opportunity)
- Aggregated player performance metrics for 2024 and 2025
- Compared year-over-year changes in usage and fantasy production to identify performance trends
- Modeled relationships using a star schema to enable dynamic filtering

## Dashboard Highlights
- Fantasy point leaderboards by position and team across seasons
- Interactive filters for position, team, and season
- Usage and efficiency-based metrics (targets, rush attempts, fantasy points per opportunity)
- Year-over-year fantasy point comparisons (2024 vs 2025)
- Identification of consistent performers, 2025 breakouts, and regression risks
- High-level KPIs summarizing league-wide fantasy production trends

## Future Improvements
- Incorporate weekly-level data to enable game-level trend analysis
- Add matchup and opponent strength features
- Expand modeling to include tight ends and defensive players
- Explore regression-based or probabilistic approaches for forward-looking projections
- Automate data refreshes for ongoing season updates
