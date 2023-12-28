# Ad Campaign Analysis

## Project Overview
This repository contains Python code for an extensive analysis of a marketing campaign dataset, providing valuable insights for the marketing team to evaluate the campaigns' effectiveness and optimize strategies.
This is a conversion campaign, with the main objective being the users' subcriptions to the platform.

## Ad Set Overview
There are 3 ad sets taregeting 3 different types of audience:
- **Hot**: Targeting the audience with the highest brand familiarity
- **Warm**: Targeting the audience with the some brand familiarity
- **Cold**: Targeting the audience with the minimal brand familiarity

## Project Structure
### Step 1: Examine the Dataset
Utilizing pandas, the code loads and explores the marketing campaign dataset.
### Step 2: Campaign Highlights
Calculation and summarization of key campaign metrics, including reach, impressions, link clicks, landing page views, results, and amount spent.
### Step 3: Ad Set Overview
Evaluation of the overall metrics of the 3 ad sets

Further segmentation of the Cold ad set: Lookalike vs Detailed Targeting
### Step 4: Detailed Ad Set Analysis
Focused analysis on Hot, Warm, and Cold ad sets.
Evaluation of top-funnel, mid-funnel, and bottom-funnel metrics with visualizations.


## Key Insights
### 1. Overall Campaign Metrics
- **Reach:** The campaign reached approximately 450,000 unique people.
- **Impressions:** Generated around 1.1 million impressions.
- **Link Clicks:** Received approximately 5,589 clicks.
- **Landing Page Views:** Experienced around 2,985 views.
- **Results:** Achieved a total of 83 results.
- **Amount Spent:** The campaign spent 4,362 EUR.

### Observation & Recommendation:
- **Engagement Efficiency**: Despite the high number of link clicks (5.6K), there is a noteworthy drop in landing page views (2.9K). Further investigation is recommended to optimize the user journey and boost conversion rates.

- **Results and ROSA**: A total of 83 results were achieved at a cost of 4,362 EUR, emphasizing the need for a detailed breakdown of results to assess campaign success.


### 2.Ad Set Overview Metrics
- **Hot audience**: The Hot audience exhibits a higher conversion rate and lower CPR, indicating effective targeting of individuals with high brand familiarity.
- **Warm audience**: The Warm audience demonstrates the highest impression, suggesting opportunities for enhanced engagement and lower CPR for individuals with some brand familiarity.
- **Cold audience**: The Cold audience achieves the highest reach. However, a low conversion rate and high CPR suggests that it would benefit from optimization to improve cost efficiency and engagment.

### 3.Detailed Ad Set Analysis
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

