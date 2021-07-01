![remodeling photo](images/cover_hammer.jpg)

# Statistical Inference of House Pricing in King County, Washington

---
**Authors**: Chandler O'Neal, Killian Kahalley, and Griffin Riner
---

## Overview

This project's focus was directed towards offering Empire Home Remodeling (EHR) insight into King County, Washington's housing market in terms of the most beneficial addition for remodeling homes. The project observed one table of housing information containing a total collection of 21,597 houses and 21 columns, these columns were then consolidated to two separate models based on the house locations within King County [rural and urban]. The model for urban King County focused on relating price to house square footage, grade (quality rating), waterfront (view of the water), whether each house had a basement or not, and the ratio of bathrooms to bedrooms. The model for rural focused on relating price to house square footage, grade, whether each house had a basement or not. This analysis can be useful to provide Empire Home Remodeling with renovation proposals that would yield the most profitable returns.

---

## Business Problem

EHR may benefit from directing their funding towards in urban King County, towards adding a basement, increasing house square footage, increasing grade, obtain waterfront view if view was previously obstructed, add a basement, and ensure a low ratio of bathrooms to bedrooms. In rural King County, EHR may benefit from increasing house square footage, and increasing grade.

---

## Data

The given table contained housing information which included the square footage of the property and home, latitude and longitude, waterfront view, basement or no basement, and other various other house attributes as number of floors and grade. 

---

## Methods

This project uses inferential analyses to identify the relationship between the data's variables (house information) and price. The inferential analyses used was the ordinary least squares linear regression model. 

---

## Results

Budgets above 150 million dollars have a stronger correlation with profit that those below 150 million. 

![regression plot](images/regression.png)

---

The 10 Actors that appeared in 10 or more of the most profitable films tended to be in a film with a mean profit above 30 million dollars.

![actor bar plot](images/bar_plot.png)

---

The 20 most successful movies filtered by budget over 150 million dollars, tomatometer rating above 85, and profit above 300 million dollars had a consistent tomatometer status of Certified-Fresh.

![top 20 bar plot](images/20_bar_plot.png)

---

The 10 actors with the highest average profit appeared in the most successful 80% of the time. 

![pie plot](images/pie_plot.png)


---

## Conclusions


This analysis offers three recomendations to Microsoft Corporation to increase their success rate in film production.

* Produce a minimum budget for each film of least 150 million dollars and or ensure the best quality possible using budget. 

* Seek out actors who have been present in ten or more highly profitable films; the analysis provided that actors who have been present in such highly profitable films have offered a higher success rate for ongoing films.



---

## Next Steps


Further analysis could offer more in-depth predictions to increase the likelihood of film success and profitablility

* Insight to suggested budget based off film length 

* A descriptive analysis of particularly undesired outcomes based on films that have failed in the industry.


---

## For More Information


Please review our full analysis in [our Jupyter Notebook](./movie_analysis.ipynb) or our [presentation](./presentation_Analysis.pdf).

For any additional questions, please contact **Jordan Jones & jtjones1@bsc.edu, Chandler O'Neal & jchandleroneal@gmail.com**


---

## Repository Structure


```
├──data/zippedData                     <- The tables used for this project 
├──images                              <- The images used 
├──src                                 <- The table links used 
├──.gitignore       
├──README.md                           <- The README for project summary
├──??.ipynb                     <- The links of the tables used for this project 
├──??.ipynb                <- Narrative documentation of analysis in Jupyter notebook
└── ?presentation?.pdf           <- PDF version of project presentation
```