# Programme Performance and Audience Engagement Analysis

## Project Overview

This project analyses programme viewership data from March to May 2025 to explore programme-level performance, monthly viewing trends, and daily audience activity.

The analysis uses Python for data preparation, programme title standardisation, aggregation, and visualisation to identify patterns in viewership across the period.

## Objectives

- Identify the most-viewed programmes based on total views.
- Compare monthly viewership across March, April, and May 2025.
- Explore daily viewing patterns and fluctuations over time.
- Summarise key findings and identify opportunities for further analysis.

## Tools and Technologies

- **Python** — data preparation and analysis
- **Pandas** — data manipulation and aggregation
- **Regular Expressions (Regex)** — programme title extraction
- **Data Visualisation** — programme performance and viewership trends
- **Jupyter Notebook** — interactive analysis and documentation

## Methodology

1. **Data consolidation:** Combined viewership records across the three-month period.
2. **Data cleaning:** Standardised programme titles using a master lookup reference.
3. **Title extraction:** Applied regular expressions to extract programme titles where lookup matches were unavailable.
4. **Programme analysis:** Compared total views across programme titles.
5. **Trend analysis:** Examined monthly totals and daily viewing patterns.
6. **Reporting:** Summarised the findings and outlined recommendations for further investigation.

## Key Findings

- **Top-performing programme:** Bradley Walsh recorded 238,138 views in the analysed data.
- **Monthly viewership:** March 2025 recorded 1,553,854 views, compared with 1,146,918 in April and 1,140,700 in May.
- **Daily viewing patterns:** The time-series visualisation showed a prominent peak in March, followed by lower daily view counts and smaller fluctuations in April and May.
- **Programme-level variation:** The programme ranking showed differences in total views across the listed titles.

## Recommendations for Further Analysis

- Monitor the performance of leading programmes over time.
- Compare viewing patterns with programme release dates and scheduling information, where available.
- Track monthly viewership across a longer period to determine whether the observed changes persist.
- Examine how total views are distributed across the programme catalogue.
- Validate unmatched content codes and extracted programme titles to maintain data quality.

## Project Files

| File | Description |
|---|---|
| `programme-performance-analysis.ipynb` | Notebook containing the data preparation, analysis, and visualisations |
| `programme-performance-report.pdf` | Report summarising the methodology, findings, charts, and recommendations |

## Conclusion

This project demonstrates a structured approach to data cleaning, exploratory analysis, and visualisation to understand programme performance and audience viewing activity. The findings provide a descriptive overview of viewership patterns and a foundation for further investigation.

*Note: The findings describe patterns in the available data. Additional information would be needed to establish the causes of observed viewership changes.*
