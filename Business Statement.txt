Description
Business Context
The advent of e-news, or electronic news, portals has offered us a great opportunity to quickly get updates on the day-to-day events occurring globally. The information on these portals is retrieved electronically from online databases, processed using a variety of software, and then transmitted to the users. There are multiple advantages of transmitting new electronically, like faster access to the content and the ability to utilize different technologies such as audio, graphics, video, and other interactive elements that are either not being used or aren’t common yet in traditional newspapers.

E-news Express, an online news portal, aims to expand its business by acquiring new subscribers. With every visitor to the website taking certain actions based on their interest, the company plans to analyze these actions to understand user interests and determine how to drive better engagement. The executives at E-news Express are of the opinion that there has been a decline in new monthly subscribers compared to the past year because the current webpage is not designed well enough in terms of the outline & recommended content to keep customers engaged long enough to make a decision to subscribe.

[Companies often analyze user responses to two variants of a product to decide which of the two variants is more effective. This experimental technique, known as A/B testing, is used to determine whether a new feature attracts users based on a chosen metric.]

Objective
The design team of the company has researched and created a new landing page that has a new outline & more relevant content shown compared to the old page. In order to test the effectiveness of the new landing page in gathering new subscribers, the Data Science team conducted an experiment by randomly selecting 100 users and dividing them equally into two groups. The existing landing page was served to the first group (control group) and the new landing page to the second group (treatment group). Data regarding the interaction of users in both groups with the two versions of the landing page was collected. Being a data scientist in E-news Express, you have been asked to explore the data and perform a statistical analysis (at a significance level of 5%) to determine the effectiveness of the new landing page in gathering new subscribers for the news portal by answering the following questions:

Do the users spend more time on the new landing page than on the existing landing page?
Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
Does the converted status depend on the preferred language?
Is the time spent on the new page the same for the different language users?
 

Data Dictionary
The data contains information regarding the interaction of users in both groups with the two versions of the landing page.

user_id - Unique user ID of the person visiting the website
group - Whether the user belongs to the first group (control) or the second group (treatment)
landing_page - Whether the landing page is new or old
time_spent_on_the_page - Time (in minutes) spent by the user on the landing page
converted - Whether the user gets converted to a subscriber of the news portal or not
language_preferred - Language chosen by the user to view the landing page


Scoring guide (Rubric) - E-news ExpressEvaluated
Criteria	Ratings	Points
Define the problem and perform an Exploratory Data Analysis
- Problem definition, questions to be answered - Data background and contents - Univariate analysis - Bivariate analysis
Well Done. Answered to the point	8/8
Illustrate the insights based on EDA
Key meaningful observations on individual variables and the relationship between variables
EDA is done well, observations are mentioned as required	6/6
Do the users spend more time on the new landing page than the old landing page?
- Perform visual analysis - Formulate null and alternative hypotheses - Select the appropriate test - Calculate the p-value - Write the inference based on the p-value
Good Work. All steps related to hypothesis testing are done in a methodical manner	10/10
Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?
- Perform visual analysis - Formulate null and alternative hypotheses - Select the appropriate test - Calculate the p-value - Write the inference based on the p-value
Good Work. All steps related to hypothesis testing are done in a methodical manner	10/10
Does the converted status depend on the preferred language?
- Perform visual analysis - Formulate null and alternative hypotheses - Select the appropriate test - Calculate the p-value - Write the inference based on the p-value
Good Work. All steps related to hypothesis testing are done in a methodical manner	10/10
Is the mean time spent on the new page same for the different language users?
- Perform visual analysis - Formulate null and alternative hypotheses - Select the appropriate test - Calculate the p-value - Write the inference based on the p-value
Good Work. All steps related to hypothesis testing are done in a methodical manner Visual Representation is performed as required You have chosen the right test One-Way ANOVA, for this problem. But its advisable to solve assumptions of ANOVA related to DATA NORMALITY and VARIANCE by conducting Shapiro-Wilk Test and Levene Test. After these tests are conducted and results are taken into consideration, then proceed to ANOVA	10/10
Overall Notebook Quality
- Structure and flow - Well commented code - Conclusion and Business Recommendation
Very good presentation. Very good illustration of graphs. Conclusions/recommendations/observations are mentioned in a meticulous manner Provide business recommendations	6/6
