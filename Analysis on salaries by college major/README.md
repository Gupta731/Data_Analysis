### College degrees are very expensive. 
But, do they pay you back? Choosing Philosophy or International Relations as a major may have worried your parents, but does the data back up their fears? PayScale Inc. did a year-long survey of 1.2 million Americans with only a bachelor's degree. 
We'll be digging into this data and use Pandas to answer these questions:


1. Which degrees have the highest starting salaries? 

1. Which majors have the lowest earnings after college?

1. Which degrees have the highest earning potential?

1. What are the lowest risk college majors from an earnings standpoint?

1. Do business, STEM (Science, Technology, Engineering, Mathematics) or HASS (Humanities, Arts, Social Science) degrees earn more on average?


### Today's Learning Points


1. Use .head(), .tail(), .shape and .columns to explore your DataFrame and find out the number of rows and columns as well as the column names.

1. Look for NaN (not a number) values with .findna() and consider using .dropna() to clean up your DataFrame.

1. You can access entire columns of a DataFrame using the square bracket notation: df['column name'] or df[['column name 1', 'column name 2', 'column name 3']]

1. You can access individual cells in a DataFrame by chaining square brackets df['column name'][index] or using df['column name'].loc[index]

1. The largest and smallest values, as well as their positions, can be found with methods like .max(), .min(), .idxmax() and .idxmin()

1. You can sort the DataFrame with .sort_values() and add new columns with .insert()

1. To create an Excel Style Pivot Table by grouping entries that belong to a particular category use the .groupby() method


