# group2_am10.mam2024

Proposal: Global Black Money Transactions 
Using the data found on this website: https://www.kaggle.com/datasets/waqi786/global-black-money-transactions-dataset
we want to create a storyline visualising illicit financial transactions. 

The data includes:
Transaction ID: Unique identifier for each transaction. (e.g., TX0000001)
Country: Country where the transaction occurred. (e.g., USA, China)
Amount (USD): Transaction amount in US Dollars. (e.g., 150000.00)
Transaction Type: Type of transaction. (e.g., Offshore Transfer, Property Purchase)
Date of Transaction: The date and time of the transaction. (e.g., 2022-03-15 14:32:00)
Person Involved: Name or identifier of the person/entity involved. (e.g., Person_1234)
Industry: Industry associated with the transaction. (e.g., Real Estate, Finance)
Destination Country: Country where the money was sent. (e.g., Switzerland)
Reported by Authority: Whether the transaction was reported to authorities. (e.g., True/False)
Source of Money: Origin of the money. (e.g., Legal, Illegal)
Money Laundering Risk Score: Risk score indicating the likelihood of money laundering (1-10). (e.g., 8)
Shell Companies Involved: Number of shell companies used in the transaction. (e.g., 3)
Financial Institution: Bank or financial institution involved in the transaction. (e.g., Bank_567)
Tax Haven Country: Country where the money was transferred to a tax haven. (e.g., Cayman Islands)

We will look at which countries (incl. tax haven country) have the highest number of illicit financial transactions.
What the most frequent source of money is, which industries are most prevalent in illicit activities.
The transaction type, the risk score, and the average number of shell companies involved. 

Here are some topics we are thinking of doing:
1. High-Risk Industries for Black Money Transactions
Question: Which industries have the highest black money transaction amounts and money laundering risk scores?
Variables: Industry, Amount (USD), Money Laundering Risk Score
Analysis: Group by industry, calculate total transaction amounts and average risk scores, and identify high-risk industries.

2. Impact of Shell Companies on Money Laundering Risk
Question: Is there a correlation between the number of shell companies involved and the money laundering risk score?
Variables: Shell Companies Involved, Money Laundering Risk Score
Analysis: Group by the number of shell companies, calculate the average risk score for each group, and observe trends in risk scores based on shell company involvement.

3. Effect of Money Source on Risk and Transaction Type
Question: How do different sources of money (e.g., illegal vs. legal) vary in terms of risk scores and transaction types?
Variables: Source of Money, Money Laundering Risk Score, Transaction Type
Analysis: Group by source of money and transaction type, calculate the average risk score, and analyze if illegal funds are concentrated in specific transaction types.

4. Transaction Volume for Specific Financial Institutions
Question: Are there financial institutions frequently involved in high-value black money transactions?
Variables: Financial Institution, Amount (USD)
Analysis: Group by financial institution, calculate the total transaction volume for each, and identify institutions involved in high-value transactions.

5. Frequency of Tax Haven Countries Usage
Question: Which tax haven countries are most commonly used in black money transactions?
Variables: Tax Haven Country
Analysis: Count occurrences of each tax haven country to identify the most frequently used locations.

6. Transaction Patterns by Person Involved
Question: Are specific individuals frequently associated with high-risk transaction patterns or high transaction amounts?
Variables: Person Involved, Amount (USD), Money Laundering Risk Score
Analysis: Group by individuals, calculate total transaction amounts and average risk scores for each, and identify high-risk participants.

7. Transaction Type and Money Laundering Risk
Question: Are certain transaction types (e.g., offshore transfers or stock transfers) associated with higher money laundering risk scores?
Variables: Transaction Type, Money Laundering Risk Score
Analysis: Group by transaction type, calculate the average risk score for each type, and identify high-risk transaction types.
