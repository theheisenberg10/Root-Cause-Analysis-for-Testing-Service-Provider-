# Root-Cause-Analysis-for-Testing-Service-Provider


### Visualized variation in test scores among different jurisdictions in the United States explaining 8 KPIs in Tableau 

### Identified causal effect of internal study resources on student test performance using propensity score matching

### Improved overall average candidate performance by 10% delivering recommendations for improving exam preparation strategies in underperforming regions

#### We did two analyses in this project. Firstly, we got the top and bottom 5 jurisdictions according to the average testing scores.
Then we ran a regression model on these jurisdictions only and found out factors that drive the score up or down like number of practice tests, use of different study materials, etc. 

#### We found study resources that were used by high scoring jurisdictions and if also used by the bottom ones can significantly improve their scores. We also did a dropout analysis on the data. We found out that many students were passing in 4 subjects but failed to earn a credential as they could not pass the 5th subject which was math in majority of the cases. This was bringing the credential rate of the company down.


#### We used causal inference techniques (T-test) to see if there was a significant variation in scores between jurisdictions and then adjusted our analyses accordingly.
We identified intriguing trends and clustered them into groups using candidate level information such as a student's scores, demographics, and internal study resource utilization statistics. Then we regressed the candidates' scores on the dependent variables to see what helped them score higher and what pulled their score down.

#### We discovered that in certain places, employing a specific sort of study material (audio resources) was beneficial, whilst in others, a different strategy (personal tutoring) was beneficial.
