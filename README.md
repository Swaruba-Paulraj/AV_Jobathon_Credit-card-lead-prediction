# AV_Jobathon_Credit-card-lead-prediction
# Credit Card Lead Prediction
Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings.
The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc. 
In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.
Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given:
    Customer details (gender, age, region etc.)
    Details of his/her relationship with the bank (Channel_Code,Vintage, 'Avg_Asset_Value etc.)
### About:

In business today, generation of leads could help save resources like time and money and increase the revenue. Moreover, if the business is able to correctly identify the customers of different segments and cross sell their products, it would obviously improve the business revenue, customer satisfaction, customer life time value through a deeper integration in a customer’s business.

Thus, generating leads for cross selling becomes a great strategy for both the business and the customer, creating a Win-Win.

### Problem Statement:

The client is a happy bank with different kinds of bank accounts such as investment account, savings account, NRI accounts, fixed deposit account and so on. The idea is to find if the bank can do cross sales of the credit products among the customers of a different account.

Thus, the problem statement is to classify the customers and find if they will be interested to buy a credit card or not and their probability of getting the credit card.

## Data Dictionary
### Train Data
#### Variable	Definition

ID->	Unique Identifier for a row

Gender->	Gender of the Customer

Age	->Age of the Customer (in Years)

Region_Code	->Code of the Region for the customers

Occupation->	Occupation Type for the customer

Channel_Code ->Acquisition Channel Code for the Customer  (Encoded)

Vintage	-> Vintage for the Customer (In Months)

Credit_Product->	If the Customer has any active credit product (Home loan,Personal loan, Credit Card etc.)

Avg_Account_Balance	-> Average Account Balance for the Customer in last 12 Months

Is_Active	->If the Customer is Active in last 3 Months

Is_Lead(Target)	-> If the Customer is interested for the Credit Card
0 : Customer is not interested
1 : Customer is interested


### Test Data
#### Variable	Definition

ID->	Unique Identifier for a row

Gender -> Gender of the Customer

Age ->	Age of the Customer (in Years)

Region_Code	-> Code of the Region for the customers

Occupation -> Occupation Type for the customer

Channel_Code ->	Acquisition Channel Code for the Customer  (Encoded)

Vintage ->	Vintage for the Customer (In Months)

Credit_Product ->	If the Customer has any active credit product (Home loan,Personal loan, Credit Card etc.)

Avg_Account_Balance ->	Average Account Balance for the Customer in last 12 Months

Is_Active ->	If the Customer is Active in last 3 Months

### Output file:
Variable	Definition

ID	->Unique Identifier for a row

Is_Lead	(Target) ->Probability of Customer showing interest (class 1)

