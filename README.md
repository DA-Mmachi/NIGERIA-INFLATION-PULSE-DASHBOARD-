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
- [Limitations](#limitations)
- [Author Information](#author-information)
  
## Project Overview
---
####  Nigeria has been dealing with high inflation for years, but many people don’t fully understand what is causing it or how it affects the economy. This project uses data and a dashboard to explain how different economic factors like oil prices, exchange rates, and interest rates have influenced inflation in Nigeria from 2010 to 2024. Amid rising inflation and economic reforms, this dashboard was built to answer a critical policy and economic question, "What is driving inflation in Nigeria, and what has changed over the years?

[Dashboard](Nigeria's Inflation Pulse Dashboard)

![Screenshot 2025-06-18 162703](https://github.com/user-attachments/assets/5a56cc10-f384-4c19-b2a8-48aace747d6c)


## Data Sources

The data for this project was sourced from credible, publicly available platforms:

- Central Bank of Nigeria (CBN) -Monetary Policy Rate (MPR), FX Rates

- National Bureau of Statistics (NBS) -Inflation and GDP Data

- World Bank Open Data -Brent Crude Oil Prices (Annual Avg.)

- Period: 2010 to 2024

  ## Data Tools

 - Microsoft Excel - For dashboard creation, data visualization, slicer interactivity
  
 -  Pivot Tables - Metric aggregation and summary computation ie analyzing data
  
 - Excel Charts - Line charts, combo charts, scatter plots for trend correlation and showing reltionships

 - Slicers - For selecting diffrent years interactively

## Data Cleaning / Preperation

- Cleaned and standardized raw data using Microsoft Excel to ensure consistency and accuracy for analysis.
  
- Merged datasets from multiple sources (NBS, CBN, World Bank)

- Transformed data into consistent yearly formats

- Converted all currency data to the same unit (₦ per $)

- Created a unified base table for analysis

  ## Exploratory Data Analysis

- How did inflation behave during oil price crashes and reforms? ![Screenshot 2025-06-18 164031](https://github.com/user-attachments/assets/4c37c7f0-26aa-4cd7-9b72-4082512bbbb5)


- Did naira losing value make the inflation worse? [Results/Findings](#results--findings)

- Did higher MPR control inflation effectively? [Results/Findings](#results--findings)

- How strong is the correlation between oil prices and inflation? [Results/Findings](#results--findings)

- Which macro variables showed the strongest predictive trend ie which factor seems to affect inflation the most?[Results/Findings](#results--findings) 

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

- Exchange rate affects inflation the most based on this analysis as the naria weakens (₦/$ increases), imported goods and fuel became more expensive. Nigeria depends heavily on imports, so a weak naira quickly drives up prices across the economy. This was especially clear in 2023 and 2024 after currency reforms. ![Screenshot 2025-06-18 165445](https://github.com/user-attachments/assets/b70e4966-4194-4f1e-80b2-fdd105d08f47)


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

  ## Limitations

- The analysis uses annual data, which limits short-term trend detection.
- Focused only on key macroeconomic indicators; fiscal and structural factors were not included.
- Policy impacts may take time to reflect, and lag effects may not be fully captured.
- Built in Excel for accessibility; advanced modeling is outside the scope.

  ## Author Information
### Mmachi Goodness Paul-Emeka
### Economist | Data Analyst | Excel & Power BI Specialist


 ### Thanks for checking out this project! Feel free to reach out:

-  Email:
[mmachipaulemeka@gmail.com](mailto:mmachipaulemeka@gmail.com)
-  Linkedin:
[Mmachi Goodness Paul- Emeka](https://www.linkedin.com/in/mmachi-goodness-paul-emeka)
