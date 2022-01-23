# Health-Insurance-Cross-Sell-Prediction
Our client is an Insurance company that has provided Health Insurance to its customers now they need help in predicting whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.
Using descriptive, diagnostic, and visualization – statistical, graphical analysis in Python to predict if prior health insurance policyholders of an insurance business will be interested in purchasing automobile insurance from the firm. 
Identifying the prospective client base will allow the firm to build its communication strategy to reach out to those consumers and improve its business model and revenue accordingly.

DATA DICTIONARY
VARIABLE - DEFINITION

id : Unique ID for the customer

Gender : Gender of the customer

Age : Age of the customer

Driving_License : 0 : Customer does not have DL, 1 : Customer already has DL

Region_Code : Unique code for the region of the customer

Previously_Insured : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

Vehicle_Age : Age of the Vehicle; 1-2 Year : 0, < 1 Year : 1, > 2 Years : 2

Vehicle_Damage : 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

Annual_Premium : The amount customer needs to pay as premium in the year

PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage : Number of Days, Customer has been associated with the company

Response : 1 : Customer is interested, 0 : Customer is not interested
