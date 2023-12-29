# Ad Campaign Analysis

## Project Overview
This repository contains Python code for an extensive analysis of a marketing campaign dataset, providing insights for the marketing team to evaluate the campaigns' effectiveness and optimize strategies.
This is a conversion campaign, with the objective being the users' subcriptions to the platform.

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
### Ad Set Overview 
- **Hot audience**: The Hot audience exhibits a higher conversion rate and lower CPR, indicating effective targeting of individuals with high brand familiarity.
- **Warm audience**: The Warm audience demonstrates the highest impression, suggesting opportunities for enhanced engagement and lower CPR for individuals with some brand familiarity.
- **Cold audience**: The Cold audience achieves the highest reach. However, a low conversion rate and high CPR suggests that it would benefit from optimization to improve cost efficiency and engagment, which in turn could improve conversion rate.
  #### Lookalike vs Detailed Targeting:
  Upon analyzing the performance of subcategories within the Cold audience, the following findings emerged:
  - **Detailed Targeting**: This subcategory exhibits a more focused approach, resulting in a higher average number of results (4.25) and a relatively lower Cost Per Result (CPR) of 53.26 EUR. The targeting precision of this segment contributes to a cost-effective conversion strategy.

  - **Lookalike Audience**: While achieving slightly fewer average results (3.75), this subcategory showcases a noteworthy characteristic—broader reach. The Lookalike Audience reaches a more extensive group of individuals who share characteristics with the brand's known audience. This broader exposure, despite a marginally lower result count, presents an opportunity for increased brand exposure and potential engagement.

  - **Recommendation**: Consider a balanced approach by leveraging the precision of Detailed Targeting for focused results and exploring the potential of the Lookalike Audience for broader brand exposure. Further analysis of engagement quality and future conversion potential within the broader audience can guide strategic adjustments for maximizing campaign effectiveness.

### Detailed Ad Set Analysis
#### Hot Audience
- **Top-Funnel Metrics:** Reach, Impressions, CPM.

- **Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.
- **Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

#### Warm Audience
- **Top-Funnel Metrics:** Reach, Impressions, CPM.
- **Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.
- **Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

#### Cold Audience
- **Top-Funnel Metrics:** Reach, Impressions, CPM.
- **Mid-Funnel Metrics:** CTR (all), Landing Page Views, CPC.
- **Bottom-Funnel Metrics:** Results, CPR, Amount Spent.

## Recommendations
Based on the analysis, here are actionable recommendations for optimizing future campaigns:
- **Optimize Ad Creatives:** Enhance ad creatives to improve relevance and engagement.
- **Refine Audience Targeting:** Adjust audience targeting to better align with campaign objectives.
- **Budget Allocation:** Consider reallocating budgets based on the performance of different audience segments.
- **Landing Page Optimization:** Evaluate and optimize landing pages to improve conversion rates.
Recommendations
User Journey Optimization: Investigate the drop in landing page views post link clicks to identify friction points and optimize the user journey.

Ad Set Budget Reallocation: Consider reallocating budget among Hot, Warm, and Cold ad sets based on their performance to maximize ROI.

Creative Testing: Explore variations in ad creatives to understand their impact on engagement and conversion rates.

Audience Refinement: Evaluate the performance of Lookalike Audience targeting to refine and optimize for better results.

Data-Driven Decision Making: Regularly analyze and adapt strategies based on ongoing campaign performance for continuous improvement.
