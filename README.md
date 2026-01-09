## Overview
This project analyzes NFL fantasy football performance data from the 2024 regular season and evaluates how well data-driven projections from 2024 predict actual player performance during the 2025 season. Using historical usage and efficiency metrics, I built predictive fantasy point estimates and compared them against real 2025 results to assess model accuracy. The project demonstrates an end-to-end sports analytics workflow, combining data modeling, exploratory analysis, and performance evaluation using Power BI.

## Final Project
(final project will be uploaded page by page when project is completed)

## Objectives
- Analyze NFL fantasy performance using 2024 season data
- Engineer fantasy scoring and usage-based metrics
= Build fantasy point projections from historical performance
= Compare 2024-based projections to actual 2025 season results
= Evaluate prediction accuracy and identify over- and under-performing players
= Create an interactive Power BI dashboard for exploration and comparison

## Tools
- Power BI for data modeling, DAX measures, and visualization
- CSV-based NFL player datasets (QB, RB, WR)
- Git/GitHub for version control and documentation

## Methodology
- Loaded and cleaned position-specific NFL datasets (QB, RB, WR)
- Built a unified player lookup table to support relational modeling
- Created custom DAX measures for PPR fantasy scoring
- Aggregated player performance metrics from the 2024 season
- Generated fantasy point projections using historical usage and efficiency data
- Imported partial 2025 season data and calculated actual fantasy outcomes

## Dashboard Highlights
- Fantasy point leaderboards by position and team
- Interactive filters for position, team, and season
- Usage-based metrics (targets, rush attempts, expected completion rate, etc.)
- Projected vs actual fantasy point comparisons (2024 → 2025)
- Identification of players who exceeded or underperformed expectations
- High-level KPIs summarizing total fantasy production and prediction accuracy

## Future Improvements
- Incorporate weekly-level data to improve projection granularity
- Add matchup and opponent strength features
- Expand modeling to include tight ends and defensive players
- Explore regression-based or machine learning fantasy projections
= Automate data refreshes for ongoing season updates
- Compared projected vs actual performance to measure prediction error
- Modeled relationships using a star schema to enable dynamic filtering
