# A-B_Test
A/B testing for an international online store


## Project Description

We've received an analytical task from an international online store. The predecessor failed to complete it: they launched an A/B test and then quit. They left only the technical specifications and the test results.

## Technical description

* Test name: recommender_system_test
* Groups: А (control), B (new payment funnel)
* Launch date: 2020-12-07
* The date when they stopped taking up new users: 2020-12-21
* End date: 2021-01-01
* Audience: 15% of the new users from the EU region
* Purpose of the test: testing changes related to the introduction of an improved recommendation system
* Expected result: within 14 days of signing up, users will show better conversion into product page views (the product_page event), product card views (product_card) and purchases (purchase). At each of the stage of the funnel product_page → product_card → purchase, there will be at least a 10% increase.
* Expected number of test participants: 6000

## Study Goals:

* Download and preprocess test data
* Determine whether the A/B test was performed correctly.
* Analyze the results.
* Provide insights and recommendations to the client.
