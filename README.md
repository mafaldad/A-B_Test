# A/B Test: Recommender System Evaluation

**Overview:** This project analyzes an incomplete A/B test conducted by an international online store. The test, named recommender_system_test, aimed to evaluate a new payment funnel by testing the impact of an improved recommendation system on user conversion rates through key events: product page views, product card views, and purchases. The task involved downloading, preprocessing, and analyzing test data to determine whether the A/B test was performed correctly and to provide insights and recommendations based on the results.

**Technical Specifications:**
* Test Groups: Group A (control) vs. Group B (new payment funnel)
* Launch Date: 2020-12-07
* End Date: 2021-01-01
* Test Audience: 15% of new users from the EU region
* Expected Results: At least a 10% increase in conversion rates across the funnel stages (product page → product card → purchase) within 14 days of user registration.

**Data Sources:**
* Marketing Events
* New Users
* Event Logs
* Participants

**Data Preprocessing:**

* Ensured all date columns were correctly formatted and handled missing and duplicate values.
* Verified that participants met the requirement for the EU region's specified 15% new users.
* Merged relevant datasets to prepare for further analysis.

**Exploratory Data Analysis (EDA):**

* Analyzed event distribution across key stages: login, product_page, product_cart, purchase.
* Visualized the user funnel and observed both groups' conversion rates at each stage.
* Temporal analysis of user activity revealed peaks around crucial dates leading to the holiday season.

**A/B Test Analysis:**

* Tested for statistically significant differences in conversion rates between groups using Z-tests.
* Conducted a Bonferroni correction to adjust for multiple hypothesis testing.

**Results:**

* The only significant difference was in the purchase event, with Group A showing a higher conversion rate than Group B.
* After applying the Bonferroni correction, no statistically significant differences were found.

**Conclusion:**
The new recommendation system did not significantly improve conversion rates. Therefore, it is recommended that we revert to the previous system to maintain engagement and optimize purchase conversions.

**Skills:**

* A/B Testing
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Hypothesis Testing
* Python (Pandas, NumPy, Scipy, Matplotlib, Plotly)
