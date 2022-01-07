# Mouse Tumor Treatment Study Analysis
<img src="Images/cancer-treatment.jpg" width="600">

<br />

### Summary

249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

<br />

### Outline of steps perfomed for analysis
* Merged Mice and Study Datasets.
* Checked if any mice had duplicated values.
* Dropped single mouse found with duplicate values from data set.
* Created Summary Statistics datframe for each Drug Regimen.
* Created bar chart for Number of Timepoints vs Drug Regimen.
* Created pie chart showing distribution of Male and Female mice.
* Got Tumor volume for each mouse at last timepoint.
* Used for loop to perform statistical analysis on each drug regimen data to analyse for outliers.
* Generated a boxplot from the results.
* Created a line plot for Tumor Volume vs Timpoint for a specific Mouse ID that was treated with Capomulin.
* Generated a scatter plot of average tumor volume 

<br />

### Examples of plots produced

<img src="Images/Plots/barplot.png" width="300">
<img src="Images/Plots/pieplot.png" width="300">

<br />

<img src="Images/Plots/boxplot.png" width="300">
<img src="Images/Plots/lineplot.png" width="300">

<br />

<img src="Images/Plots/scatterplot.png" width="300">

<br />

### Some Observations and Insights

* Pearsonr Correlation:
The correlation of Tumor Volume (mm3) with Mouse Weight (g) is: 0.84, indicating a Strong correlation.
* Ramicance and Capomulin have more time points potentially indicating the mice live longer
* The sex distribution is almost equal so there is a good balance of sexes, comrising 49.6% females and 50.4% males
* Capomulin and Ramicane had smaller Final Tumor Volumes compared to Infubinol and Ceftamin
* Ceftamin had a larger range of Final Tumor Volumes compared to Capomulin, Ramicane, and Infubinol
* Infubinol group had a single outlier - should be investigated

<br />
<br />
<hr />
<br />

<img width="150" src="https://drive.google.com/uc?export=view&id=1OH_TvDjISYpoKL_98Jx3CDFPM7Xp8J6H">

### Abz Raja
abzraja@gmail.com


