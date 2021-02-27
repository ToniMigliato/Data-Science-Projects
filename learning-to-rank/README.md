# Learning to Rank

# Ranking Potential Customers

![](https://github.com/ToniMigliato/Data-Science-Projects/blob/main/learning-to-rank/images/cover_learning_ranking.jpg)
<span>Photo by <a href="https://unsplash.com/@mikepetrucci?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Mike Petrucci</a> on <a href="https://unsplash.com/s/photos/shopping?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

# 1. The Company
The company we are analysing provides health insurance for its customers and the product manager is considering the possibility of offering a new product: a car insurance. Last year, the company made a research with 380.000 customers asking them about their interest in purchasing a new car insurance. All customers showed if he/she was interested or not in acquiring the new proposal. Their answers is in a database together with other informations about the customers. The Product Team selected 127.000 new customers that didn't answered the research to participate in a marketing campaign, when they will receive an offer for the new car insurance.

## Business Problem

The company has 127.000 potential customers to accept the new car insurance proposal but is able only to call to 20.000. Which customers should the company sellers prioritize to call to? Which of the 127.000 are the 20.000 most probable to accept the new proposal?

### Business problem in terms of expected value

Knowing the customers with higher probability of accepting the new insurance proposal, the insurance company will gain efficacy and optimization of its processes by addressing your team to those customers. This gain in efficacy means optimal use of resources (people, time), which lead to the achievement of a useful goal (delivery of the proposal to the higher probability customers).

### Objective of this Project

Identify and list the 20.000 potential customers with higer propobability of accepting a new car insurance proposal.

# 2. Business Hypothesis

In order to know the problem situation better, some assumptions were made about the company and about the customers. They are:
1. The lower the age, the greater the chance of accepting the new insurance proposal.

2. Women take more insurance than men.

3. People paying a lower annual premium have a greater chance to accept new car insurance proposal.

4. Peopĺe who have already damage a car have higher probability of accepting a car insurance.

5. People with previous ensurance has greater chance to accept the car insurance proposal.

6. Regions with more traffic and accidents have more people willing to purchase car insurance.

7. People who doesn't have a driving license will not accept the new car insurance.

8. People with newer car have more chance to purchase a car insurance.

9. Older customers have higher probability to accept a proposal to purchase a car insurance from the All Insurance company.


# 3. Solution Strategy

This kind of problem is known as "learning to rank problems", in which we can use classification supervised learning techniques to create a list of customers ordered by his/her probability of purchasing the new insurance. In order to reach a solution for this problem, I plan the following steps:

1. Understand the business as a whole and this specific problem situation.

2. Make an exploratory analysis of the data to gain in-depth knowledge about the problem.

3. Prepare the data in order to make it possible to be assimilated by the models.

4. Select and apply some Machine Learning classifiers and assess the performance of those classifiers.

5. Evaluate the results and the process regarding to the business problem.

6. Show the results.

# 4. Important Insights from EDA

1. Customers that had already gotten involved in car accident is more likely to accept the new proposal.
2. Customers with previous insurance are less likely to accept the new proposal.
3. People with driving license said they would purchase the new insurance with a proportion similiar to the people without driving license. This show a relative lack of interest in general of accepting the new insurance proposal.

# 5. Machine Learning models applied

In order to solve this problem, I applied 6 Machine learning models to the data. They are:
- Logistic Regression
- Random Forest
- XGBoost
- Extra Trees
- LightGBM
- CatBoost

:wrench: Under construction! The below steps will be accomplished in the next cycles of the project.

# 6. Machine Learning performance

# 7. Business results

# 8. Conclusions

# 9. Learned lessons

# 10. Next steps