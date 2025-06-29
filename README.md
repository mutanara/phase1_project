
# Aircraft Safety Analysis – Phase 1 Project

This project investigates aircraft accident data to help aviation stakeholders identify which aircraft makes and phases of flight are most prone to fatal accidents.

## Business Understanding

Aviation regulators and airline companies need insights to improve flight safety and reduce fatalities. This project uses real aviation accident data to reveal patterns and make recommendations.

## Data Understanding

- Source: `AviationData.csv` from the Aviation Safety Reporting System
- Size: Over 80 columns, thousands of accident records
- Key features: `Make`, `Event.Date`, `Broad.Phase.of.Flight`, `Injury.Severity`, `Total.Fatal.Injuries`

## Data Preparation

- Cleaned column names
- Removed columns with more than 50% missing values
- Handled invalid or inconsistent values
- Converted date and numeric columns properly

## Visualizations

- Bar chart of injury severities
- Bar chart of aircraft makes with most fatalities
- Accidents per year (with gridlines and filtered low-frequency years)
- Accidents by flight phase (with bar labels)

## Recommendations

1. Prioritize safety training for risky flight phases like approach and landing.
2. Be cautious when purchasing aircraft makes with high fatality records.
3. Improve incident reporting and data completeness.

---

_Made by Narcisse Mutabaruka for Moringa School Phase 1 Data Science Project._
