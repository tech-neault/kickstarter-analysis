# An Analysis of Kickstarter Campaigns using Excel
## Overview of Project
### Purpose
   Our friend Louise is currently raising money for her play, and using Kickstarter to do so. She's curious about the success rates of other similar projects, and has asked us to look into it for her. In this analysis, we used data on Kickstarter-funded arts projects that vary in size and scope. By using this data to investigate the outcomes of projects similar to Louise's, we hope to give her an idea of what she can expect from her Kickstarter fundraising. 
 
 ## Analysis and Challenges
    
### Analysis of Outcomes, Based on Launch Date
!/main/assets/images/Theater_Outcomes_vs_Launch.png

Based on the launch date, we can see that there are certain months where the total number of successful Kickstarters is higher. In the month of May, we can see that there were over 100 successful launches, suggesting that May is an excellent time to begin a Kickstarter campaign. However, as the summer months pass, the successful Kickstarters decline in number, while the failed Kickstarters remain relatively steady. This suggests that the later in the summer months (June through August) the Kickstarter is launched, the less likely it is to be successful. 

### Analysis of Outcomes, Based on Goals
!/main/assets/images/Outcomes_vs_Goals.png

The goals of the fundraisers fall across a wide spectrum, with some looking to raise under $1,000 and the highest seeking $100 million. With one exception, the general trend is that fundraisers with lower goals have a higher chance of successfully raising the money they seek. The significant uptick of successfully funded Kickstarters with goals between $40,000-$44,999 suggests that the projects seeking funding in that range are more interesting to their funders. Future research into this trend may provide further insight. 

### Challenges and Difficulties Encountered

One of the main challenges faced during this analysis was ensuring a proper COUNTIFS() formula was used during the final stages of data manipulation. While initially setting the forumla up, I wasn't able to get it to work properly for the ranges. That's because I used the following formula: 

`=COUNTIFS(Kickstarter!$F:$F, "successful", Kickstarter!$R:$R, "plays", Kickstarter!$D:$D, ">=45000" Kickstarter!D$:D$, "<=49999")`

The issue with this formula is twofold: it is missing one comma, and it does not properly reference the Kickstarter worksheet in the last criteria range as the dollar signs are on the wrong side of the column designator. Using the "rubber ducky" method, where you explain what you're trying to achieve to a rubber ducky, I was able to find and correct the issues within this formula. 

## Results

### Conclusions

### Limitations

### Further Suggestions & Additional Analysis

