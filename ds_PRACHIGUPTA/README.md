# Data Science Project: Trader Behavior and Market Sentiment

This project explores the relationship between trader behavior and market sentiment using historical Bitcoin and Hyperliquid trading data. The analysis aims to uncover patterns and hidden signals that can inform smarter trading strategies.

## Project Structure

- **notebook_1.ipynb**: Data Ingestion, Cleaning, and Exploratory Data Analysis (EDA). This notebook merges the sentiment and trading datasets and generates key visualizations.Advanced Analysis: Performs in-depth analysis on trader performance, correlations, and hypothesis testing.
- **csv_files/**: Contains the raw datasets and the cleaned, merged data file.
- **outputs/**: Stores all generated charts and plots.
- **ds_report.pdf**: A final report summarizing the project's methodology, findings, and conclusions.

## Key Findings

- **Sentiment Distribution**: The dataset contains a high number of trades during "Fear" and "Greed" periods, with "Fear" being the most common sentiment.
- **Trading Volume**: The highest trading volume occurred during "Fear" periods, followed by "Greed." This suggests that traders are most active during periods of high market uncertainty or emotion.
- **PnL Distribution**: The distribution of PnL (Profit and Loss) appears to be similar across all sentiment categories. The vast majority of trades cluster around zero PnL, with outliers representing large profits or losses.
- **Buy vs. Sell Trades**: The number of trades during "Fear" periods was higher than during "Greed" periods, with a relatively even split between Buy and Sell trades.
- **Correlation**: A weak positive correlation exists between trading volume (Size USD) and Closed PnL, but there is no significant correlation between sentiment and profitability.

This analysis suggests that, for this dataset, overall market sentiment does not strongly predict a trader's profitability. Instead, factors like trading volume seem to be more weakly correlated with PnL. The report provides a more detailed breakdown of these findings.