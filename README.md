# Bringing-Customers-Home

**Problem Statement**

Build two predictive models:

* B2B customer conversion (classification): Whether a B2B customer will purchase or not in the next 30 days
* B2B customer expected revenue (regression): How much a B2B customer will spend in the next 30 days

**Scope**:
* Marketing team can build customized campaigns and promotion plan for each customer
* Easy to market or give discounts , once know likelihood of purchase
* Achieve customer growth and therefore sales increase 
* Customer retention, reducing customer churn by targeting customers who were undecided but could still be persuaded
* Saving money incurred on marketing & promotion

**Data**:

* Training data – 28K rows and 184 columns

 + convert_30 (boolean) – did customer purchased in next 30 days
 
 + revenue_30 (numeric) -  revenue from customer in next 30 days
 
 + Features- customer ID, country, past orders, past orders with no issues, quotes, visit and activities on website,  calls and emails with company, day since Enrolled and Net Promoter Score

* Holdout data – 30K rows and 182 columns - includes features and no outcome variables for a different set of customers

