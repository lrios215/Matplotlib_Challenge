### Matplotlib_Challenge
GT Data Bootcamp - Matplotlib HW_Rios

### Pymaceuticals Inc.: Summary of the most recent animal study treated with a variety of drug regimens. 

Study Overview: In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

This summary shows technical tables and figures needed for the technical report of the overall study and overall trends.

### Overall Observations and Inferences
* * Out of all the drug regimens, Capomulin and Ramicane had the lowest mean tumor volume (mm3) of 40.68 & 40.22, also the lowest variance (24.95, 23.49) and standard error (0.33, 0.32).  While the highest mean tumor volume, variance and standard error were from mice tested with Ketapril and Naftisol (see Table 1).

* Out of the four most promising drug regimens: Capomulin, Ramicane, Infubinol, and Ceftamin, Capomulin and Ramicane had comparable low end tumor volumes and both had significantly lower IQRs then Infubinol and Ceftamin (see Figures 3 and 4).

* When mouse weight and average tumor volume were plotted from the mice treated with Capomulin there was a high positive correlation between increase in weight and increase in end tumor volume (mm3), with the correlation coefficient being 0.84 (see Figure 6).

### Technical Summary

* Data for any mouse ID with duplicate time points was remove any data associated with that mouse ID.  There was one mouse ID removed due to duplicate time points: Mouse ID g989.  Total of 248 amice were used for data analysis.

* Table 1: Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![Table 1: Summary Stats for Each Drug Regimen](figures/summary_drug_regimens.png)

* Figure 1 shows the number of total mice for each treatment regimen throughout the course of the study.

![Figure 1: Total Number of Mice per Regimen](figures/barplottotalmice.png)

* Figure 2 shows the total percentage of male versus female mice
![Figure 2: Total Percentage of Male vs Female Mice](figures/sexofmice.png)

* Figure 3 shows the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin and the quartiles and IQR, to quantitatively determine if there are any potential outliers across all four treatment regimens.

![Figure 3: Quartiles and IQR of Most Promising Treatments](figures/iqr_four_regimens.png)

* Figure 4 shows a box and whisker plot of the final tumor volume for all four treatment regimens and highlights any potential outliers in the plot with a star.

![Figure 4: Potential Outliers](figures/lasttumorvol.png)

* Figure 5 shows the tumor volume versus time point for one mouse that was treated with Capomulin.

![Figure 5: One Mouse Tumor Volume vs Time Point for Capomulin](figures/onemousetumorvol_capomulin.png)

* Figure 6 shows a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.  With the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment and the linear regression model.

![Figure 6: Mouse Weight vs Average Tumor Volume for Capomulin](figures/linregcopomulin.png)

* The r-squared is: 0.8419363424694718
* The equation for linear regression is: y=0.95x + 21.55


 
