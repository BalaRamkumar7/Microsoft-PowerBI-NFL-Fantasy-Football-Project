## Overview
This project analyzes NFL fantasy football performance data across the 2024 and 2025 regular seasons to identify year over year trends in player usage, efficiency, and production. Using multi-season fantasy and opportunity metrics, I built an interactive Power BI dashboard to compare player performance across seasons and explore what these patterns suggest for 2026 expectations. Rather than producing deterministic predictions, the project emphasizes trend-based analysis and forward-looking insights grounded in historical performance.

## Final Project
(final project will be uploaded page by page when project is completed)

## Objectives
- Analyze NFL fantasy football performance across the 2024 and 2025 seasons
- Engineer usage and efficiency-based metrics to support year-over-year comparison
- Identify stable performers, breakout candidates, and regression risks
- Examine how changes in usage and efficiency impact fantasy production
- Create an interactive Power BI dashboard to explore trends and infer 2026 outlooks

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

## Dashboard Highlights
- Fantasy point leaderboards by position and team across seasons
- Interactive filters for position, team, and season
- Usage and efficiency-based metrics (targets, rush attempts, fantasy points per opportunity)
- Year over year fantasy point comparisons (2024 vs 2025)
- Identification of consistent performers, breakout candidates, and regression risks
- High-level KPIs summarizing league-wide fantasy production trends

## Future Improvements
- Incorporate weekly-level data to improve projection granularity
- Add matchup and opponent strength features
- Expand modeling to include tight ends and defensive players
- Explore regression-based or probabilistic approaches for 2026 projections
- Automate data refreshes for ongoing season updates
- Compared projected vs actual performance to measure prediction error
- Modeled relationships using a star schema to enable dynamic filtering
