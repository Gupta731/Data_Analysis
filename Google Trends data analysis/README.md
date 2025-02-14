## Combining Google Trends with other Time Series Data

## What can the popularity of search terms tell us about the world? Google Trends gives us access to the popularity of Google Search terms. Let's investigate:
1. How search volume for "Bitcoin" relates to the price of Bitcoin.
1. How search volume for a hot stock like Telsa relates to that stock's price and
1. How searches for "Unemployment Benefits" vary with the actual unemployment rate in the United States.

## What we will learn today
1.How to make time-series data comparable by resampling and converting to the same periodicity (e.g., from daily data to monthly data).
1.Fine-tuning the styling of Matplotlib charts by using limits, labels, linestyles, markers, colours, and the chart's resolution.
1.Using grids to help visually identify seasonality in a time series.
1. Finding the number of missing and NaN values and how to locate NaN values in a DataFrame.
1. How to work with Locators to better style the time axis on a chart.
1. Review the concepts learned in the previous three days and apply them to new datasets.

## Learning Points & Summary
1. How to use .describe() to quickly see some descriptive statistics at a glance.
1. How to use .resample() to make a time-series data comparable to another by changing the periodicity.
1. How to work with matplotlib.dates Locators to better style a timeline (e.g., an axis on a chart).
1. How to find the number of NaN values with .isna().values.sum()
1. How to change the resolution of a chart using the figure's dpi
1. How to create dashed '--' and dotted '-.' lines using linestyles
1. How to use different kinds of markers (e.g., 'o' or '^') on charts.
1. Fine-tuning the styling of Matplotlib charts by using limits, labels, linewidth and colours (both in the form of named colours and HEX codes).
1. Using .grid() to help visually identify seasonality in a time series.

<img src="https://img-c.udemycdn.com/redactor/raw/2020-10-10_11-31-21-6f077e81c843cdfb085899620891eaf3.png">
