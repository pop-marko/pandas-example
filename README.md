# Series transformation
## Netflix Titles Practice 
This is my first repo where I focused on Pandas Series. I wanted to understand and learn how Series works before moving on to DataFrames.

What I messed around with:
- Filtering: I pulled out everything released between 2000 and 2010.
This is where I realized 'AND' python keyword can't work here, but '&' does the job
(plus the parenthesis which i've put in python too, nothing new with them).
- Connecting Two Series: I used column release_year to grab data from column names title. Pandas keeps the original indexes, so you always know which title belongs to which year, and i love it.
- Finding Insights: I found the oldest movie in the database using .min() and linked it back to its title.
