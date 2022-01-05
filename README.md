# A-B-Testing_-International_Online_Store

## Task
It is an analytical task from an international online store. It was started, but failed to complete: they launched an A/B test and then quit (to start a watermelon farm in Brazil). They left only the technical specifications and the test results.

## Technical description
- Test name: interface_eu_test
- Groups: А (control), B (new payment funnel)
- Launch date: 2020-12-07
- Date when they stopped taking up new users: 2020-12-30
- End date: 2021-01-01
- Audience: 15% of the new users from the EU region
- Purpose of the test: testing changes related to the introduction of an improved recommendation system
- Expected result: within 14 days of signing up, users will show better conversion into product page views (the product_page event), instances of adding items to the shopping cart (product_cart), and purchases (purchase). At each stage of the funnel product_page → product_cart → purchase, there will be at least a 10% increase.
- Expected number of test participants: 6000
