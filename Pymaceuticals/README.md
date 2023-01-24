# Pymaceuticals Inc. Data Analysis 
By Kiana Navarre

**Programming Language Used: Python/Matplotlib**

## Description
This project uses Pandas and Matplotlib to examine experimental data resluting from a series of drug trials observing the effects of a range of drug regimen in mice.  The dataset used in this project represents the results of an animal study perfomed by a faux pharmaceutical company (Pymaceuticals, Inc.) specializing in anti-cancer medications and focusing on potential treatments for squamous cell carcinoma (SCC). This study was performed on 248 mice over the course of 45 days and focused on tumor development and volume. 

## Analysis Summary
- The Capomulin and Ramicane drug regimens were perfomed with more total mice than the other drug regimens.  This increased sample size indicates that the results for these drug regimens may be slightly more representative of the drug's performance than those perfomed with a smaller mice population.  
- Looking at the distribution of female vs. male mice examined throughout this study, it appears to be split evenly with males making up 51% of the total population and females making up the remaining 49%.  As a follow-up to this analysis, it would be beneficial to examine the distribution of female vs. male mice for each drug regimen in order to exclude sex as an influencing factor. 
- Final tumor volume for the Capomulin and Ramican regimens were significantly smaller than the final tumor volumes for the Infubinol and Ceftamin regimens.  Assuming that smaller tumor volume equates to a healthier mouse, this indicates that the Capomulin and Ramican regimens were more effective than the Infubinol and Ceftamin regimens. 
- There is a strong correlation positive correlation (0.84) between mouse weight and average tumor volume for the mice in the Capomulin regimen.  Increased mouse weight correlates to a larger tumor volume. 

## PyCity School Analysis Details: 
These conclusions were made by looking at the results of the analyses listed below. 

### Summary Statistics
A summary statitstics table was generated calculating the following properties for each drug regimen:
- Mean Tumor Volume
- Median Tumor Volume
- Tumor Volume Variance
- Tumor Volume Standard Deviation
- Tumor Volume Standard Error (SEM)

The following plots/figures were also generated to further analyze the data presented: 
- a bar graph plotting the total number of timepoints for all mice tested for each drug regimen 
- a pie chart showing the distribution of female vs. male mice 
- a box plot showing the distribution of tumor volume for the treatment groups:
  - Capomulin
  - Ramicane
  - Infubinol
  - Ceftamin
- a line plot of tumor volume vs. time for a mouse (Mouse ID = l509)treated with Capomulin
- a scattter plot of average tumor volume vs. mouse weight for the Capulin regimen
  - this plot also contains a line of best fit with a correlation value of 0.84
