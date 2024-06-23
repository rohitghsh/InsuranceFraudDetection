# Insurance Fraud Detection

## Guided by : 
Dr. Dave Wanik - OPIM 5512: Data Science Using Python - University of Connecticut

## Challenge: 
This dataset comes from the 2023 NESS Statathon (Theme 1). Here is a link to where the live competition was hosted!

https://www.kaggle.com/competitions/2023-travelers-ness-statathon/overview

You work for Travelers Insurance Company's fraud detection department as a modeler. Your colleagues, who are not familiar with statistics, would like you to create a predictive model based on historical claim data. Your team is concerned about the fraud detection accuracy as well as the key drivers that cause fraudulence.
For this case competition, I was tasked with identifying first-party physical damage fraudulence and explaining the indicators of fraudulent claims.


## Dataset Description
All first-party physical damage claims will be filtered by claim handlers and some of them will be referred to the fraud detection team. The data is a sample of these referred claims from 2015 to 2016.


## Variable Descriptions

claim_number - Claim ID (cannot be used in model)

age_of_driver - Age of driver

gender - Gender of driver

marital_status - Marital status of driver

safty_rating - Safety rating index of driver

annual_income - Annual income of driver

high_education_ind - Driver’s high education index

address_change_ind - Whether or not the driver changed living address in past 1 year

living_status - Driver’s living status, own or rent

zip_code - Driver’s living address zipcode

claim_date - Date of first notice of claim

claim_day_of_week - Day of week of first notice of claim

accident_site - Accident location, highway, parking lot or local

past_num_of_claims - Number of claims the driver reported in past 5 years

witness_present_ind - Witness indicator of the claim

liab_prct - Liability percentage of the claim

channel - The channel of purchasing policy

policy_report_filed_ind - Policy report filed indicator

claim_est_payout - Estimated claim payout

age_of_vehicle - Age of first party vehicle

vehicle_category - Category of first party vehicle

vehicle_price - Price of first party vehicle

vehicle_color - Color of first party vehicle

vehicle_weight - Weight of first party vehicle

fraud - Fraud indicator (0=no, 1=yes). This is the response variable.
