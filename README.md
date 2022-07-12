# HousinginNL
My first documentation about current housing prices in three main cities in the Netherlands. 
I scraped the data of NL Housing Market though Pararius(dot)com using Python and converted it into CSV file. 
Then, using pandas_profiling env, I run three lines of python code to import ProfileReport show dataset statistics 
which useful to investigate on data's correlation, missing values and possibilities for further EDA process.

More to check:
1. CSV result does not show all available listings on the website, hence small data created.
2. Because of #1, difficult to check detailed correlations between each data values.
