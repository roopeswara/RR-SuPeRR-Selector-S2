# Rajasthan Royals SupeRR Selector S2
### Mobile Analytics Hub – Pressure Reliability System & Strategy

## 1. Project Overview

The **Rajasthan Royals SupeRR Selector S2** is a web-based cricket analytics dashboard designed to evaluate player performance under pressure and support player selection and auction strategy.

The dashboard presents player rankings, the Royals Pressure Reliability Index (RPRI), high-pressure performance statistics, auction recommendations, and model methodology in a responsive interface.

It also includes a dedicated **Pressure Top 10** section displaying the top 10 batters and bowlers using tile-based cards.

## 2. Key Features

### A. ML & Methodology
- Overview of the Royals Pressure Reliability Index (RPRI).
- Dynamic leverage and pressure scoring methodology.
- Empirical Bayes shrinkage explanation.
- Batter and bowler RPRI formulas.
- Workload and player fitness audit methodology.

### B. Pressure Top 10
- Top 10 high-pressure batters.
- Top 10 high-pressure bowlers.
- Individual player ranking cards.
- RPRI scores.
- High-pressure strike rates for batters.
- High-pressure economy rates for bowlers.
- Special visual emphasis for the top three players.

### C. Player Cards & Why Picked
- Separate batter and bowler rankings.
- Player search functionality.
- Player cards and table views.
- Individual player information.
- RPRI comparison chart.
- Player selection reasoning.

### D. Auction Blueprint
- Auction strategy recommendations.
- Squad bottleneck analysis.
- Suggested player targets.
- Role-based filtering of auction recommendations.

### E. Model Stability
- Dedicated model stability and audit section.

### F. Unstop Key
- Displays player names, IDs, and RPRI scores.
- Individual player information can be copied.
- Provides a full submission key for the top 10 batters and bowlers.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure |
| CSS3 | Styling and responsive layouts |
| Tailwind CSS | Utility-based styling |
| JavaScript | Interactive functionality and data rendering |
| Chart.js | RPRI comparison charts |
| Font Awesome | Icons |
| Google Fonts | Typography |

## 4. How to Run the Project

This is a standalone HTML dashboard. No separate backend or database setup is required to view the current version.

1. Download `RR_SupeRR_Selector_Pressure_Top10.html`.
2. Save the file on your computer.
3. Open the file using a modern web browser such as Google Chrome, Microsoft Edge, or Opera.
4. Wait for the external styling and chart libraries to load.
5. Navigate through the dashboard using the tabs at the top.

**Important:** An active internet connection is required to load the external libraries, icons, and fonts from their CDNs.

## 5. Dashboard Navigation

| Section | Purpose |
|---|---|
| ML & Methodology | Understand the RPRI model and pressure calculations |
| Pressure Top 10 | View the top 10 high-pressure batters and bowlers |
| Player Cards & Why Picked | Explore player rankings, statistics, and selection reasoning |
| Auction Blueprint | Review auction targets and squad recommendations |
| Model Stability | Explore model stability and audit information |

## 6. RPRI – Royals Pressure Reliability Index

RPRI is presented as a composite performance index intended to evaluate player reliability under high-pressure match situations.

The dashboard displays separate formulas for batters and bowlers.

### Batter RPRI
The batter formula considers:
- Empirical Bayes strike rate.
- Empirical Bayes batting average.
- Boundary contribution.
- Dot-ball percentage.
- Performance step-up.
- Consistency.

### Bowler RPRI
The bowler formula considers:
- Empirical Bayes economy rate.
- Empirical Bayes strike rate.
- Dot-ball percentage.
- Boundary percentage.
- Spell performance.
- Economy savings.

The dashboard describes the resulting index on a 0–100 scale.

## 7. Data and Accuracy Disclaimer

The dashboard contains player statistics, rankings, and model-related information embedded in its JavaScript data.

The Pressure Top 10 section displays the rankings and figures supplied for this project. These figures are not independently verified by the dashboard.

The dashboard is currently a front-end analytics presentation. It does not independently process the complete ball-by-ball dataset or execute a live machine-learning pipeline when opened.

Any use of player rankings or auction recommendations for actual selection decisions should involve independent verification of the underlying data, calculations, and player availability.

## 8. Project Structure

The current project is delivered as a single HTML file:

```text
RR_SupeRR_Selector_S2/
│
└── RR_SupeRR_Selector_Pressure_Top10.html
```

The HTML file contains:
- Page structure
- Dashboard styling
- JavaScript player datasets
- Ranking and filtering logic
- Pressure Top 10 card rendering
- Chart rendering
- Interactive modals and clipboard functions

## 9. Future Improvements

Possible future enhancements include:

- Integration with a live cricket statistics database.
- Automated ball-by-ball data processing.
- Real-time RPRI calculation.
- Interactive player comparison.
- Advanced performance visualizations.
- Downloadable player reports.
- Backend integration for storing datasets.
- Automated player fitness and workload updates.

## 10. Conclusion

The Rajasthan Royals SupeRR Selector S2 dashboard provides a structured interface for exploring pressure-based cricket performance, player rankings, and auction strategy.

By combining the RPRI methodology, player statistics, interactive cards, charts, and auction recommendations, the project aims to support more informed, data-driven cricket player evaluation.

---

**Project:** Rajasthan Royals SupeRR Selector S2  
**Module:** Pressure Reliability System & Strategy  
**Version displayed in dashboard:** RPRI Engine v2.4  
**Format:** Single-page HTML web application
