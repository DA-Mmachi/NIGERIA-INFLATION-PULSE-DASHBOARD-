# Nigeria's Inflation Pulse (2010–2024): Tracking Oil Prices, Exchange Rates & Policy Impact

## Table of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Data Tools](#data-tools)
- [Data Cleaning/Preperation](#data-cleaning--preperation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis Approach](#data-analysis-approach)
- [Results/Findings](#results--findings)
- [Recommendations](#recommendations)
- [References](#references)
- [Author Information](#author-information)
  
## Project Overview
---
####  Nigeria has been dealing with high inflation for years, but many people don’t fully understand what is causing it or how it affects the economy. This project uses data and a dashboard to explain how different economic factors like oil prices, exchange rates, and interest rates have influenced inflation in Nigeria from 2010 to 2024. Amid rising inflation and economic reforms, this dashboard was built to answer a critical policy and economic question, "What is driving inflation in Nigeria, and what has changed over the years?

## Data Sources

The data for this project was sourced from credible, publicly available platforms:

- Central Bank of Nigeria (CBN) -Monetary Policy Rate (MPR), FX Rates

- National Bureau of Statistics (NBS) -Inflation and GDP Data

- World Bank Open Data -Brent Crude Oil Prices (Annual Avg.)

- Period: 2010 to 2024

  ## Data Tools

1. Microsoft Excel - For dashboard creation, data visualization, slicer interactivity
  
2. Pivot Tables - Metric aggregation and summary computation ie analyzing data
  
3. Excel Charts - Line charts, combo charts, scatter plots for trend correlation and showing reltionships
  
4. Slicers - For selecting diffrent years interactively

## Data Cleaning / Preperation

- Cleaned and standardized raw data using Microsoft Excel to ensure consistency and accuracy for analysis.
  
- Merged datasets from multiple sources (NBS, CBN, World Bank)

- Transformed data into consistent yearly formats

- Converted all currency data to the same unit (₦ per $)

- Created a unified base table for analysis

  ## Exploratory Data Analysis

- How did inflation behave during oil price crashes and reforms?

- Did naira losing value make the inflation worse?

- Did higher MPR control inflation effectively?

- How strong is the correlation between oil prices and inflation?

- Which macro variables showed the strongest predictive trend ie which factor seems to affect inflation the most?

  ## Data Analysis Approach

Here’s how I anaswered these questions:
- Trend Analysis: I used Line graphs and combo charts show inflation over time and its movement against other variables.

- Correlation Analysis: I Used scatter plots with R² (coefficient of determination) values to measure strength of relationships and how strong the connection between inflation and oil price is in each period

- I grouped the data for inflation and oil prices across three major periods:

   - Pre-shock (2010–2014)

   - Oil Crash & COVID (2015–2020)

   - Reform & Inflation spike (2021–2024)

- Economic Storytelling: I added annotations to describe trends and insights clearly.

- Slicers: I included Slicers for year-by-year comparison.

## Results / Findings

- Inflation vs Exchange Rate: ₦ devaluation triggered inflation spikes, especially post-2023 FX reform. Strong pass-through effect observed.This means that as the naira became weaker (₦/$ went up), inflation rose sharply especially in 2023 and 2024. This shows that a weaker currency made things more expensive.

- Inflation vs MPR: Despite rising interest rates, inflation kept increasing → suggests cost-push inflation. This means that inflation wasn't just caused by too much money it was also due to higher cost of goods and services.

- Inflation vs Oil Price: Weak correlation during 2015–2020 (R² = 0.13), stronger post-2021 (R² = 0.71) due to subsidy reform and fuel price hike. ie to say that oil prices didn't have much impact on inflation between 2015-2020 inflation was affected by other factors.But from 2021, when fuel subsidies were removed, inflation rose showing that fuel price changes started to affect inflation more.

- Inflation Trend: Inflation remained moderate before 2015, spiked in 2016, and sharply increased from 2022 to 2024. That is to say that Inflation was low before 2015,increased after the oil crash,stayed unstable during COVID, and spiked again from 2022-2024 due to reforms and subsidy removal.

  ## Recommendations

Based on the analysis, here are some actionable suggestions:

- Improve FX stability: Inflation closely follows naira depreciation. Managing FX volatility is crucial to inflation control. When the naira loses value, prices go up fast. Government and the Central Bank should work on keeping the naira more stable.

- Diversify inflation control strategy: MPR alone is ineffective. Address supply-side and structural inflation factors. Since inflation is mostly caused by rising cost (not just money sipply), there is need to invest in agriculture,electricity,and transport to reduce cost.

- Policy timing matters: Sudden reforms (e.g., subsidy removal) can trigger inflation spikes if not phased properly. Removing fuel subsidy suddenly caused a shock. Future reforms should be introduced step-by-step to avoid sharp inflation spikes.

- Raising MPR alone didn't stop inflation. A mix of monetary and non monetary strategies is needed.

 ## References

- Central Bank of Nigeria (CBN)

- National Bureau of Statistics (NBS)

- World Bank Data Bank

  ## Author Information
### Mmachi Goodness Paul-Emeka
### Economist | Data Analyst | Excel & Power BI Specialist
  
