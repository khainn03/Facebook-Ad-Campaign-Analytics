# Ad Campaign Analysis
## Table of Contents

1. [Project Overview](#project-overview)
2. [Ad Set Overview](#ad-set-overview)
3. [Code Structure](#code-structure)
4. [Campaign Overview](#campaign-overview)
   - [Observation & Recommendation](#observation--recommendation)
5. [Ad Set Insights](#ad-set-insights)
   - [Ad Set Overview](#ad-set-overview-1)
     - [Lookalike vs Detailed Targeting](#lookalike-vs-detailed-targeting)
   - [Detailed Ad Set Analysis](#detailed-ad-set-analysis)
6. [Conclusion](#conclusion)
   - [Key Highlights](#key-highlights)
   - [High-Level Recommendations](#high-level-recommendations)

## Project Overview
This repository contains Python code for an extensive analysis of a marketing campaign dataset, providing insights for the marketing team to evaluate the campaigns' effectiveness and optimize strategies.
This is a conversion campaign, with the objective being the users' purchases to the platform.

## Ad Set Overview
There are 3 ad sets taregeting 3 different types of audience:
- **Hot**: Targeting the audience with the highest brand familiarity
- **Warm**: Targeting the audience with the some brand familiarity
- **Cold**: Targeting the audience with the minimal brand familiarity

## Code Structure
### Step 1: Examine the Dataset
Utilizing pandas, the code loads and explores the marketing campaign dataset.
### Step 2: Campaign Highlights
Calculation and summarization of key campaign metrics.
### Step 3: Ad Set Overview
Evaluation of the overall metrics of the 3 ad sets

Further segmentation of the Cold ad set: Lookalike vs Detailed Targeting
### Step 4: Detailed Ad Set Analysis
Focused analysis on Hot, Warm, and Cold ad sets.
Evaluation of top-funnel, mid-funnel, and bottom-funnel metrics with visualizations.


## Campaign Overview
- **Reach:** The campaign reached approximately 450,000 unique people.
- **Impressions:** Generated around 1.1 million impressions.
- **Link Clicks:** Received approximately 5,589 clicks.
- **Landing Page Views:** Experienced around 2,985 views.
- **Results:** Achieved a total of 83 results.
- **Conversion Rate**: 1.49 %
- **Amount Spent:** The campaign spent 4,362 EUR.
- **CPR:** 63.75 EUR
- **CPM:** 6.55 EUR
- **CPC**: 0.98 EUR



### Observation & Recommendation:
- **Engagement Efficiency**: Despite the high number of link clicks (5.6K), there is a noteworthy drop in landing page views (2.9K).  A targeted analysis of the transition from clicks to page views can unveil optimization strategies for enhanced conversion rates.

- **Results and ROSA**: A total of 83 results were achieved at a cost of 4,362 EUR, resulting in a CPR of 63.75 EUR. It's crucial to perform a detailed breakdown of results to assess the efficiency of the campaign. This would also allow an objective evaluation of the CPM and CPC to determine if these cost metrics require optimization, aligning  with the campaign's overarching goals. A recommendation would to consider the relationship between CPC and the quality of clicks, ensuring that the investment aligns with the campaign's conversion objectives.

## Ad Set Insights
## Ad Set Overview 
- **Hot audience**: The Hot audience exhibits a higher conversion rate and lower CPR, indicating effective targeting of individuals with high brand familiarity.
- **Warm audience**: The Warm audience demonstrates the highest impression, suggesting opportunities for enhanced engagement and lower CPR for individuals with some brand familiarity.
- **Cold audience**: The Cold audience achieves the highest reach. However, a low conversion rate and high CPR suggests that it would benefit from optimization to improve cost efficiency and engagment, which in turn could improve conversion rate.
  #### Lookalike vs Detailed Targeting:
  Upon analyzing the performance of subcategories within the Cold audience, the following findings emerged:
  - **Detailed Targeting**: This subcategory exhibits a more focused approach, resulting in a higher average number of results (4.25) and a relatively lower Cost Per Result (CPR) of 53.26 EUR. The targeting precision of this segment contributes to a cost-effective conversion strategy.

  - **Lookalike Audience**: While achieving slightly fewer average results (3.75), this subcategory showcases a noteworthy characteristic—broader reach. The Lookalike Audience reaches a more extensive group of individuals who share characteristics with the brand's known audience. This broader exposure, despite a marginally lower result count, presents an opportunity for increased brand exposure and potential engagement.

  - **Recommendation**: Consider a balanced approach by leveraging the precision of Detailed Targeting for focused results and exploring the potential of the Lookalike Audience for broader brand exposure. Further analysis of engagement quality and future conversion potential within the broader audience can guide strategic adjustments for maximizing campaign effectiveness.

## Detailed Ad Set Analysis
### 1. Hot Audience : 'Last day', 'Last chance & crsl', 'Discount'
**Top-Funnel Metrics:** Reach, Impressions, CPM.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/4d8f238a-0256-42db-8599-78fa5a250e22)

- The 'Last chance & crsl' ad set received the highest reach and impressions, suggesting high spend on this ad within the hot audience segment.


**Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/cd0ccb60-d895-4017-b400-b5ce841d0038)

- The 'Last chance & crsl' stood out in terms of engagement, receiving the highest CTR and landing page views within the hot audience segment.

**Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/f3ea5e7a-ba21-4dba-9b77-1edcc8a8091c)


- The 'Last chance & crsl' ad set received the highest result of 20 conversions.
- The 'Discount' ad set's CPR is the lowest, making it the most cost-efficient in terms of getting purchases from customers.
- The 'Last day' ad set  is the worst performing in terms of both conversions and CPR. Consider pausing the ad set and reallocating campaign budget.
- Over 600 EUR was spent on the 'Last chance & crsl' ad set, compared to the spending on the 'Discount' of just over 200 EUR.


#### Insights and Recommendations for the Hot Audience:

- **Engagement Focus:** Given the outstanding performance of the 'Last chance & crsl' ad set in terms of reach, impressions, CTR, and landing page views, consider replicating its elements in other creatives for overall campaign improvement.

- **Budget Reallocation:** Consider pausing the 'Last day' ad set due to its poor performance in both conversions and CPR and reallocating its budget to other high-performing ad sets

- **Cost Efficiency Evaluation:** Continue monitoring the 'Discount' ad set's performance as its low CPR indicates cost-effectiveness. Assess the potential of increasing budget for this set or replicating its strategy in other creatives for further conversions.

- **Ad Spend Alignment with Objective:** Reevaluate the budget allocation for the 'Last chance & crsl' ad set, ensuring that its high spending aligns with the desired conversion outcomes. Explore ways to maintain efficiency while scaling.



  

### 2. Warm Audience: 'CRSL', 'Video'

**Top-Funnel Metrics:** Reach, Impressions, CPM.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/782772dd-8fe9-4512-bad1-3d96a5886fdc)

- The 'CRSL' ad set performs better in all top-funnel metrics within the warm audience segment.

**Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/ce253b29-e7b7-44a0-8275-17a51393f727)

- The 'Video' ad set has a higher CTR and a lower CPC, suggesting higher engagement from the audience. However, the 'Video' ad set only has 185 landing page views, compared to 'CRSL' with 357 landing page views.

  - **Link CLicks:**
  
  ![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/78225979-21fc-42f3-9348-4be05f172643)


  - 'Videos' ad set has a higher link clicks of approximately 800, compared to that of 'CRSL' of 600.
  -  Despite higher initial engagement, 'Videos' ad set shows a significantly lower number of landing page views (800 link clicks to 185 landing page views), suggesting a bottleneck in the user's journey.




**Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/ba076f89-2ba7-4151-b82e-1a1337f4184b)

- The 'CRSL' ad set receives a higher number of conversions at a lower CPR, indicating higher cost-effectiveness.
- Conversely, the 'Video' ad set might experience fewer conversions and less cost-effectiveness due to users not reaching the landing page
- Spending a similar amount of money on both ad sets (approximately 430 EUR), the 'CRSL' ad set is more cost-effective in terms of conversions.

#### Insights and Recommendations for the Warm Audience:

- **Engagement vs. Conversion Balance:** Address the discrepancy in landing page views for the 'Video' ad set despite higher initial engagement. Conduct a thorough analysis of the user journey to optimize the conversion process.

- **Budget Reallocation:** Consider pausing the 'Video' ad due to its challenges in converting link clicks to landing page views and reallocating its budget to other high-performing ads within the warm audience segment.




### 3. Cold Audience: T1, T2, T3, T4 between 'Lookalike' and 'Detailed Targeting'
**Top-Funnel Metrics:** Reach, Impressions, CPM.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/3ead379e-74cb-4a5f-9db2-c3adc32eca55)

- T1 is the worst-performing ad set from both subcategories in terms of top-funnel metrics.
- Lookalike ad sets are bringing in more awareness.


**Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/01408851-c5c1-4331-a7ee-b0072a9d2bc5)

- T1 ad sets from both subcategories have the highest CTR but also the highest CPC, suggesting a more narrow target audience group. Consider finding a balance between volume and quality.
- T3 and T4 ad sets from both subcategories show the lowest CPC, indicating cost-effectiveness in terms of engagement.



**Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

![image](https://github.com/khainn03/Facebook-Ad-Campaign-Analytics/assets/149082730/95f325f2-de10-442e-8407-e2ebf594ace8)

- In the Lookalike subcategory, T4 is the best-performing ad set with the highest number of results at the lowest cost.
- In Detailed Targeting, the T1 ad set drove the most conversions despite having the lowest reach and impressions in their subcategory, indicating a niche and high-quality audience.
- There are no results or CPR from T2 and T3 ad set from the Detailed Targeting subcategory, suggesting that the team must have paused these ad sets due to underperformance and reallocated budget
- In Detailed targeting, despite having relatively similar CPR, the team spent 915 EUR on T1 whereas the spend on T4 was 91.02 EUR. Consider reallocating budget from T1 to T4 in Detailed Targeting to test performance.
- Overall, T4 ad set seems to be the most cost effective ad set from both subcategories at driving conversions.

#### Insights and Recommendations for the Cold Audience:
- **Budget Reallocation for T1:** Reevaluate the budget allocation for T1 in both subcategories, considering its high CPC. Test reallocating budget to T4 to achieve better cost-effectiveness.
- **Reassess T2 and T3 in Detailed Targeting:** Since there are no results or CPR from T2 and T3 ad sets in Detailed Targeting, assess the performance metrics and consider reallocation or optimizations.
- **Strategic Testing:** Conduct further testing with T4 ad set, as it appears to be the most cost-effective at driving conversions. Allocate additional budget if its performance is consistent.



  
## Conclusion 

In summary, the analysis of the marketing campaign dataset has unveiled valuable insights into the performance of distinct audience segments and ad sets. The campaign, designed to drive user purchases, demonstrated commendable engagement levels, reaching approximately 450,000 unique individuals and generating over 1.1 million impressions. However, a closer examination revealed a drop in landing page views, highlighting a critical area for optimization in the transition from clicks to conversions.

### Key Highlights:
**1. Engagement Efficiency:** The campaign excelled in top and mid-funnel metrics, indicating effective targeting and resonant creatives. Nevertheless, the drop in landing page views signifies an opportunity for refining the user journey and boosting conversion rates.

**2. Results and Cost Efficiency:** With a total of 83 results achieved at a cost of 4,362 EUR, the campaign boasted a Conversion Rate of 1.49%. However, a more granular breakdown of results, CPM, and CPC is essential to ensure that the campaign's investment aligns with its conversion objectives.
**3. Audience Segmentation Impact:** Distinct audience segments—Hot, Warm, and Cold—exhibited varying conversion rates and cost efficiencies. Notably, the Cold audience, while achieving the highest reach, displayed room for improvement in conversion rates and cost-effectiveness.


### High-Level Recommendations:
**1. Optimize Conversion Pathways:** Conduct a detailed analysis of the user journey from clicks to landing page views to conversions. Implement optimizations to streamline the conversion pathway and improve overall campaign efficiency.

**2. Budget Reallocation:** Continuously monitor and reassess budget allocations based on ad set performance. Consider reallocating budgets from underperforming ad sets to those demonstrating higher conversion rates and cost efficiency.

**3. Creative Element Replication:** Identify and replicate high-performing creative elements, such as those from the 'Last chance & crsl' ad set, to enhance engagement and overall campaign performance.

**4. Balanced Approach:** Strive for a balanced approach in targeting, considering both volume and quality. Balance precision targeting with broader exposure to maximize the impact of the campaign.

**5. Strategic Testing:** Continue strategic testing, especially with ad sets like T4 in the Cold audience, to explore and capitalize on cost-effective conversion opportunities.


In conclusion, while the campaign has achieved notable success in engagement and initial conversion metrics, a strategic and data-driven approach to refine and optimize specific aspects will be instrumental in elevating overall campaign effectiveness. The outlined recommendations provide serve as suggestions for the marketing team to enhance campaign performance and achieve the desired conversion objectives.
