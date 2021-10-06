# Beauty_Habits
An analysis of Consumer Behaviour and Beauty.

### Quick Links
<a href= "https://public.tableau.com/app/profile/stephanie.m.juniper/viz/Beauty_Habits/Dashboard?publish=yes">Tableau</a>

<a href="https://docs.google.com/presentation/d/1zr0W1Iv2qmGYfFx5AMV01Xqiyhh5T5i6xiDZygsXNxc/edit#slide=id.gf540ed207d_1_8">Google Slides</a>



---
---

## Purpose
The purpose of this analysis is to investigate and confirm the relationship between customer "loves", and number of reviews against product ranking (5 stars).

The secondary purpose to discern if there is any relationship between price, Sephora exclusivity and online only status in relation to to advise a (fictitious) client what product they should launch.

### Discovery Questions
1. Firstly, we need to statistically establish whether there is a connection between reviews and loves on customer ratings. 

2. Help Juniper Beauty decide which product(s) (categories/price points) they should launch first, whether they should give Sephora exclusivity rights and if they should launch online only or both online and instore?



### Definitions
<b>Loves</b> - occur when a customer double clicks on product they like to add it to their personal “loves”.
The <b>number of reviews</b>is a count of all the individual comments left about a product
The <b>rating</b> is out of 5 stars and ranges from 0-5 in half star increments
A <b>good rating</b> is a rating that is higher than the median/mean rating.
<b>Exclusivity</b> refers to Sephora having the sole rights to distribute the product in the US.

## Analysis

Analysis used:

<b>Random Forest Classifier</b>
After performing a Random Forest Classifier model the model was able to predict the outcome (if a rating was 4.0 or higher) with an 83% accuracy.

<b>Measures of Central Tendency</b>
No matter how I sliced the data (Online only, exclusive, etc), the Mean and Median rating stayed at 4.0 Stars (Rounded to the Nearest Star)

## Results
After assessing the mean and median of the ratings (3.99 and 4, respectively). Juniper Beauty decided to use 4 star reviews or higher as their target.

After performing a Random Forest Classifier model the model was able to predict the outcome with an 83.8% accuracy,  with number of reviews, loves and price being the features of most importance. 


## Key Findings and Recommendations
My recommendations are to launch a product that is:
- Launch a Colour product 
- Retail between $22 and $30
- Available in store and online
- engage in an social marketing campaign to ensure that their existing clientele actively review and “love” their product on Sephora.com and ensure a 4.0 Star Review or higher



## Data Source
Kaggle dataset linked <a href="https://www.kaggle.com/raghadalharbi/all-products-available-on-sephora-website">here</a>


## Tools Used
Jupyter Notebook

Python

Postgres SQL

<a href= "https://public.tableau.com/app/profile/stephanie.m.juniper/viz/Beauty_Habits/Dashboard?publish=yes">Tableau</a>

<a href="https://docs.google.com/presentation/d/1zr0W1Iv2qmGYfFx5AMV01Xqiyhh5T5i6xiDZygsXNxc/edit#slide=id.gf540ed207d_1_8">Google Slides</a>

## Contact information
Stephanie Juniper


stephanie.m.juniper@gmail.com


---
---