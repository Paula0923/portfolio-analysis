## Project One: Ironhack DA

<img width="1000" alt="image" src="https://github.com/Paula0923/portfolio-analysis/blob/main/20231215-cover-quer-wirtschaft-mp-bulle-ba_r-aktienmarkt.jpg">

## Introduction:

In this project, a financial portfolio is being analyzed. In the portfolio, there are five different assets (of different investment types) and the documented investment stretches over a time of three years.

## Data:

- The portfolio consists of five assets, some of different investment types. Asset1 and Asset2 are of type "fixed income", Asset3 and Asset4 of "equity" and Asset5 is an alternative investment.
- The investments in the data stretch over three years from January 2019 until December 2021
- Asset1 and Asset4 have a higher start price (in the lower three-digit range) while the other three have a lower start price (in the lower and middle two-digit range.

## Objectives of the Analysis:

From the data, I wanted to derive conclusions on different exercises:
    - Overall performances and price developments,
    - Weightings of the different assets in the portfolio over time,
    - Weighting by Investment type over time,
    - Individual performances regarding growth rates, cumulative and annualized returns and annualized volatility,
    - Correlation between the performances between individual assets.

## Main Conclusions in Short:

- For investers with strong nerves and risk affinity, Assets 2 and 3 seem to be the right option:
    - They promise big profits.
    - But they also show a high volatility.
- Asset 1 and 4 are very stable but the returns could be even lower than the inflation, so investers should be careful here as well.
- Asset 5 could be an alternative investment as it generated good profits in the past but also a smaller tendency towards fluctuation (than Asset 2 or 3).
- Asset 2 and 3 are highly correlated and they also show similar growth rates, annualized and cumulative returns and volatilities.
- The type of the investments seems to be no explanatory factor for the performance, similarities and differences are not in-line with the type.
- At the beginning of each year great changes were made to this portfolio regarding the weighting of the five different assets.

## Detailed Findings:
### Overall:
- Visualization: Time Series Graph in the presentation and code
- All assets have a higher end value than start value, so overall the performance was positive.
- All assets show losses around March 2020, when Covid hit the stock and capital markets for the first time.
    - Asset 4 shows a greater loss in this period than the other assets.
### Daily Percentage Growth
- The assets differ greatly in their daily percentage growth rate.
- Asset 2 and Asset 3 show a very high daily volatility with minimum growth rate around 9.5-11 % and maximums between 8-9.5 %. Also the std is high for these two assets.
- Asset 1 and Asset 4 shows the lowest daily percentage growth (respectively decrease) rates.
- Even though Asset 4 showed great losses around March 2020 in the time series graph, the daily percentage growth proves to be rather stable, so the losses were made over a longer period of time.
#### Correlation between growth rates
- Visualization: A heatmap can be found in the presentation and code and also a scatterplot between Asset 2 and Asset 3.
- Asset 2 and 3 show a high correlation (linear and monotonic) regarding their growth rates, which can also be seen in the Scatterplot. They seem to be affected by the same parameters or by one another.
- Most of the others show a medium correlation (linear, the monotonic relationship is weaker in every case).
- Asset 1 stands out for the low correlation it has with all the other assets
### Portfolio Analysis
- Asset weights: Visualization 1: Individual asset weightings in an area chart. Visualization 2: Asset weights grouped by investment type. 
    - Individual weights: There were two bigh shifts in the portfolio weighting, each at the beginning of a new year. At this point, some assets were decreased and some were increased (to different degrees).
    - Grouped by investment type: Assets of the type "Equity" (Asset 3 and 4) were decreased in 2020 and then increased again to the level of 2019 in 2021. Assets of the type "Fixed Income" (Asset 1 and 2) and "Alternative" (Asset 5) were the mirror of this: increased in 2020 and then decreased again to the level of 2019 in 2021
- Cumulative Returns: (Visualized in the lineplot) Some of the assets differ greatly regarding their cumulative returns, others show great similarities:
    - All show losses in March 2020 (but Asset 1 only a very small loss). Asset 2, 3 and 5 show great losses.
    - After the "crash", Assets 2, 3 and 5 recover quickly and then increase strongly, whereas Asset 1 and 4 go back to almost the same performance than before March 2020.
    - Asset 1 is again worth mentioning as it shows very few movements in either direction. The cumulative return more or less stays the same over the period of three years (and is only slightly positive).
- Annualized Returns: The assets again differ greatly in their performances:
    - Asset 2 and 3 again show the best performances, with annualized returns of 25.39% / 17.08%
    - Asset 1 and 4 are the lowest performers (as also the analysis before pointed to) with 2.54% / 4.34%.
    - Asset 5 is in the middle with 12.47%.
- Annualized Volatility: The volatility is higher for assets with a higher annualized and cumulative return:
    - Asset 2 and 3 show the highest annualized volatilities with 19.39 and 18.86%.
    - Asset 1 and 4 shows the lowest volatility with 4.83 and 5.36%.
    - Asset 5 again is in the middle with 15.24%.

## Further information:

In the repo, you can find my presentation in which the main findings and visualizations are shown. Also, you will find my code in the Jupyter Notebooks in which additional comments and insights can be found. All the datasets used in the project are stord in the repo as well.

