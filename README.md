# Amazon_Vine_Analysis
## Purpose
The purpose of this analysis was to find out if there is any positivity bias towards reviews that are part of a paid Vine reviewer program vs the control, reviews not generated through the paid Vine paid review program. This analysis used AWS to host the database, SQL/pdADMIN to setup the database, and PySpark to run the analysis.

## Results

### Total Vine Reviews

![Vine_Count](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/Vine_rev_count.png)

### Total Non-Vine Reviews

![No_Vine_Count](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/No_Vine_rev_count.png)

### 5 Star Reviews from Vine Program

![Vine_5_Star](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/Vine_5_star.png)

### 5 Star Reviews Non-Vine Program

![No_Vine_5_Star](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/No_vine_5_star.png)

### 5 Star Review Percentage from Vine Program

![Vine_5_Star_perc](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/Vine_5_perc.png)

### 5 Star Review Percentage Non-Vine Program

![Vine_5_Star_perc](https://github.com/Beardlow/Amazon_Vine_Analysis/blob/main/No_vine_5_perc.png)

## Summary

There does seem to be a positivity bias from reviews gotten through the Vine Review Program. The 11 percentof 5 star review difference appears to be significant. A T-test could be done betweeen these tow groups, Vine reviews and non-vine reviews, to see if there is a statistically significant difference in the Star rating between these two groups. You could also group by product manufacturer to see if some manufacturers are receiving more 5 star reviews than others.
