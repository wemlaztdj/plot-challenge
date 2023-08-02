# plot-challenge
Module 5 Challenge

## Installation
```bash
pip install pandas
pip install scipy
```

Mouse_metadata.csv has Mouse ID,	Drug Regimen,	Sex,	Age_months,	and Weight (g). 

Study_results.csv has Mouse ID,	Timepoint,	Tumor Volume (mm3),	and Metastatic Sites.

## Summary Statistics
![image](https://github.com/wemlaztdj/plot-challenge/assets/19890554/fa53776d-88d7-40d6-bb33-c6fe47718ddc)

### Sex Distribution
The distribution of female versus male mice. This balanced distribution reduces the risk of bias.

![image](https://github.com/wemlaztdj/plot-challenge/assets/19890554/2e97dde7-7a77-47a6-a2f6-a22d13943b05)

### Average Final Tumor Volume
Capomulin and Ramicane have a smaller final tumor volume than Infubinol and Ceftamin.
The picture is the distribution of the tumor volume for each treatment group.

![image](https://github.com/wemlaztdj/plot-challenge/assets/19890554/7d7826fe-5f9e-418e-a819-8bf1f35de8b6)

### Mouse weight and the average tumor volume with Capomulin
This plot shows a scatter plot of mouse weight versus average tumor volume. 

There's a strong positive correlation (0.84), indicating that heavier mice tend to have larger tumors.

![image](https://github.com/wemlaztdj/plot-challenge/assets/19890554/da9446f6-df48-4de1-9389-b203a9189a81)
