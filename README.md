# Casestudy: Instacart Groceries Basket Analysis <img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/da4479c4-15da-4e94-afd5-3086e9ae64a8">

## Project Overview
An online grocery store demands an initial data and exploratory analysis to uncover information about sales patterns and suggest strategies for better customer segmentation

**Purpose & Context:**
- To provide data-driven, business-ready recommendations and solutions
- To explore the possibilities and challenges of coding with Python
- To become acquainted with Jupyter Notebook and important business standard libraries
  
<img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/3f6c604b-c745-4d29-90b9-32b4c1fee0f9">

## What was the aim?

### Objective:

- Problem: Instacart’s “one fits all” approach towards customer marketing campaigns
  - Diverse demographics and preferences of their customers demand for targeted marketing campaigns 
- Solution:
  - To provide Instacart with information on their sales patterns
  - Suggest strategies for better marketing segmentation: ensure Instacart targets the right customer profiles with the appropriate products
- Challenge:
  - To derive specific information about customers from different data sets to inform targeted marketing
 
**Meanwhile: Acquire technical and strengthen statistical knowledge** <img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/3ce98e10-c14a-4111-bc27-3d30db9c3afe">

## How long did it take? <img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/a092cf8d-f3ec-423e-ac69-4e9b0bc79045">

- Learn from scratch, develop, and apply technical skills
- Refresh statistical concepts, data preperation, and analysis strategy:
… within 6 days
- Final project deliverable: 
… within 1 1/2 day

**I managed to stay within the given time frame, but it took me a while to sort and clean all my Jupyter Notebooks and to copy the important information into the project report mask. In the future, I will immediately format my scripts after finishing my analyses and transfer my results to the report file.** 
<img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/c00753ca-c778-4e0c-96ef-d9645b6a5746">

## Who & what was involved?
<img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/9367335e-2b60-4b6d-9805-6fa3a6c1fe1d">

- Sophie Strauß, Data Analyst & Psychologist 
- Credits: Halima Saker, Tutor, and Kelvin Wellington, Mentor 
  - supported the Python and Instacart journey with their profound knowledge, helpful feedback, and industry-ready advice 
  - Stakeholder: CareerFoundry Data Analytics Program

<img width="36" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/98d89ea0-cdf3-4340-962e-344bb878dca6">

**Tools: Python, Jupyter Notebook, Anaconda, Excel**

**Skills, Methodologies:**
- Data wrangling & merging
- Deriving variables
- Grouping & aggregating data
- Visualizing in Python
- Reporting in Excel
- Population flows

## 1. The Analysis: Data & Key Questions 

**The data sets:**
- [Open-source data sets from Instacart](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)
- [Fictive customer data set](https://s3.amazonaws.com/coach-courses-us/public/courses/data-immersion/A4/A4_Data_Assets/customers.zip)
provided by CareerFoundry for learning purposes
… had to be wrangled and merged. 

The [Data dictionary](https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b) allowed for an overview of the variables. 

Variables had to be derived, 
data grouped & aggregated, 
and visualized to answer the following business questions:

- Busiest days/ hours
- Spending behavior per hour 
- Prince tag grouping
- Popularity of products/ departments
- Customer profiles

## 1. The Analysis: Workflow

#### The learning stage: 
1. Import data sets
2. Transposing data, creating a data dict, subsetting, wrangling
3. Data prep: clean datasets, consistency checks
4. Derive columns with loc function, If-statements with For-Loops
5. Grouping & aggregating columns
6. Create flag variables 
7. Visualizations in Python
<img width="399" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/8e42999f-f58a-4d1b-98d5-210bb192105d">

_Code snippets to show loc-function and a for-loop for creating flag variables_


#### Final project deliverable:
1. Address any PII data
2. Comparing customer behavior in different geographic areas
3. Exclude low-activity customers via flag variable
4. Customer profiling
4.1 Visualization to show the distribution of profiles
4.2 Aggregating max, mean, and min variables on a customer-profile level for usage frequency and expenditure
5. Comparing customer profiles with regions and departments
5.1 Comparing visualizations

_Using the following libraries:_

<img width="282" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/6f6cf6f2-dce4-42c7-95ab-4a924a497c94">

## 2. The Analysis: Skill examples

#### 2. Comparing customer behavior in different geographic areas
Instacart customers are all over the US, and I have the state residency information. How can I use this information to inform the customer segmentation?

**Solution:** 
- Create a regional segmentation of the data as a “Region” column based on the “State” column
- source: [wikipedia: List of regions of the US](https://simple.wikipedia.org/wiki/List_of_regions_of_the_United_States)

<img width="231" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/7060b2b7-989b-4c74-a3d2-09b3ff3ecddb">

- Creating region columns via For-loops:

<img width="612" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/b4197cde-22c7-48d3-a140-4bfe909edd6c">
<img width="402" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/6e463839-4d38-4fb9-bfcb-2fa7b1a6855e">

**How can I use this information to inform the customer segmentation?**

- Cross-table and stacked bar chart to visualize differences in high and low spenders:  

<img width="612" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/6e0cf064-f2a4-4820-8400-26d14f2808b7">
<img width="265" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/030cb933-d7e0-4209-b36d-e2b95a69e501">

#### 4. Customer profiling
How can I cluster customers into profiles based on the provided information?
- Creating profiling variables based on age, income, purchased goods from departments, number of dependents, “orders_day_of_the_week”, and “order_hour_of_day” columns

Challenge: 
- Find the most informative cut-offs and combinations for profiles 
- Join the department column from a further data set

How can I cluster customers into profiles based on the provided information?

**Profile approach:**
<img width="454" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/9e4fd50f-af89-4285-a7ff-1dc90eea3248">

**Python code example:**
<img width="481" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/edb8393b-c011-44a8-930c-787e39ffe73b">


**Visualization to show the distribution of profiles:**
**Age**
<img width="808" alt="Bildschirmfoto 2023-11-21 um 14 13 10" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/6b5f1a4f-1d82-4ba0-b584-8c0b58e55d62">



**Age & Income**
<img width="808" alt="Bildschirmfoto 2023-11-21 um 14 12 05" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/12c599f5-82b6-49be-8e3f-8262e0e8f596">


**In retrospective, I would now apply unsipervised machine learning/ cluster analysis  as a new approach for the clustering of profiles to take the project to the next level.**

## 3. Further selected results & recommendations

- Saturday is busiest day, followed by Friday. Tuesday and Wednesday are the slowest days. On the busiest days, people also spend most money. 
- Most purchases are made between 9 AM and 5 PM. 
- People buy more expensive goods at irregular shopping times, speaking for impulsive expenditures at night.
- **Recommendation:** Concentrate on mid-day to advertise products with reasonable prices. Impulsive spending: think about an ethical business strategy.

<img width="404" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/2e574bdd-753e-408b-9671-1de84d9af962">
<img width="404" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/60d9149c-f380-489a-bbfb-9536d4acfcc5">

**Challenge:** To create a line chart, we need a subsample, otherwise we would run into RAM/CPU issues
**Solution:** Create a random, reproducible subsample

<img width="612" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/5a10fa92-fc60-4812-9d70-394c7efe98e8">

<img width="303" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/7068b1ac-e96a-444b-b8fd-4f0b9ffc119e">

- Price density is highest among the range between 1 and 15 and is substantially lower above 15.
- **Recommendation:** Introduce two-split prince rating.

<img width="302" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/ed4f50c7-39a1-4a3f-a5f9-1655a2328145">

<img width="230" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/24187a8f-c71a-4f1a-a010-8e439f9eca2c">

_Products from produce, dairy eggs, snacks, and beverages are among the 4 most popular products._

- Differences between regions seem marginal. Further analyses should target proportional differences regarding the number of inhabitants per region. 
- The South is generally the most important region, with most "early bird" shoppers, the highest number of the most important customer group (middle-aged, moderate income), the biggest household size, most weekend shoppers, and most "preppers" and "breakfast persons" as most important profiles. 

<img width="284" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/7add063c-85b3-4af6-ae4e-e14b411cb42d">

<img width="284" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/f96cbed3-2bef-45fc-990d-62294f1f52e0">

<img width="284" alt="image" src="https://github.com/SoStrauss/SoStrauss.github.io/assets/148326046/a1b5f9e1-5010-4eac-b758-809f8fea4a1a">

## 4. Conclusion

**The project:**
Customer segmentation and targeted marketing campaigns seem reasonable considering that Instacart has customers from all US regions & states, different income classes, age ranges, household sizes, with differing product preferences…
In a next step, I would revise and complement the customer profiles based on more research & stakeholder feedback, as  differences between regions & relations to other variables seem marginal. 
My future analyses would target proportional differences regarding the number of inhabitants per region, and I would group the data by user id before creating profiles to have user profiles (instead of order profiles).

**My learning experience:**
Thanks to my basic R knowledge from my background in psychological research, I wasn’t a complete newbie to data analysis with programming languages. However, I was surprised by how intuitively and smoothly Python allowed me to derive insights.
I gained confidence in providing various businesses with data-driven solutions to problems.
In the future, I want to improve my skills in Python and learn how to write more complex, elegant, and parsimonious code

**Further ideas to enhance the strategy of Instacart:**

2. **Regression**:  Predict likelihood of customer to churn; Predict the customer lifetime value — how much are customers going to contribute towards the business over their time with us? 
3. **Classification**: Predict which products a customer is likely to buy when they come onto the e-commerce platform; **Predict whether customer will churn (Classes: Active or Churn)**


Thank you for joining me on my Instacart/ Python journey!
Find the full project including all notebooks here: 

[GitHub Repository](https://github.com/SoStrauss/Instacart)

Do not hesitate to reach out:
[mailto](http://sophie.straussq@gmail.com)
[LinkedIn](https://www.linkedin.com/in/sophie-strau%C3%9F-621a98296/)
