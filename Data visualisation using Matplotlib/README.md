## Analyse the Popularity of Different Programming Languages over Time
Each post on Stack OverFlow comes with a Tag. And this Tag can be the name of a programming language.
To figure out which language is the most popular, all we need to do is count the number of posts on Stack Overflow that are tagged with each language. The language with the most posts wins!

### Today we will learn:

1. How to visualise your data and create charts with Matplotlib

1. How to pivot, group and manipulate your data with Pandas to get it into the format you want

1. How to work with timestamps and time-series data

1. How to style and customise a line chart to your liking

### Learning Points & Summary
1. Used .groupby() to explore the number of posts and entries per programming language

1. Converted strings to Datetime objects with to_datetime() for easier plotting

1. Reshaped our DataFrame by converting categories to columns using .pivot()

1. Used .count() and isna().values.any() to look for NaN values in our DataFrame, which we then replaced using .fillna()

1. Created (multiple) line charts using .plot() with a for-loop

1. Styled our charts by changing the size, the labels, and the upper and lower bounds of our axis.

1. Added a legend to tell apart which line is which by colour

1. Smoothed out our time-series observations with .rolling().mean() and plotted them to better identify trends over time.

