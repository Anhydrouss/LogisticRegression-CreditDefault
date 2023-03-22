# Credit Default Prediction
Predicting credit default using supervised machine learning (logistic regression). Features include debt segmentation, account status, hardship, disconnection, and previous delinquency to predict likelihood of debt write-off.

# What is the Probability (%) of a Binary Outcome of Debt Write-off (bad=1, good=0)?

The level of confidence and the probability of default could be used to guide pricing at the point of sale and determine debt collection path after onboarding/billing. For example, divide results into deciles of 10 and depending on the business appetite for risk, profitability margin and market share, a line can be drawn to limit the acquisition of new customers. Other risk mitigating processes could be implemented at the point of sale such as direct debit and security deposit. Whereas after billing, high risk customers should be assigned to a shortened treatment/collection cycle with tailored communication and assigning the top collection agent to engage and negotiate payment.  

# Risk management and Debt Collection in a Nutshell: 

1) filter - limit the acquisition of known high risk profiles
2) accuracy - contract, onboard and bill accurately, first time 
3) classify - continuously monitoring and reclassifying risk with updated data 
4) engage - persistent/effective communication and skip-tracing 
5) strong negotiation tactics to secure immediate payment
6) stem the bleed (disconnection, threat of credit default listing, legal proceedings and settlements)

# Credit Risk Assessment and Management Policy Using Logistic Regression

The purpose of this policy is to establish a comprehensive framework for assessing and managing credit risk during the customer onboarding process, utilizing logistic regression as a tool to support decision-making. This policy aims to minimize the risk of default and maintain the company's annual bad debt write-off within a tolerance of 3-5%. The company is committed to maintaining a rigorous and data-driven credit risk assessment and management process during customer onboarding. We will utilize logistic regression to evaluate potential customers' credit risk, setting specific thresholds to ensure our risk tolerance is maintained. 

Training and Compliance:
All employees involved in the customer onboarding process must be trained on this policy and the use of logistic regression for credit risk assessment. Compliance with this policy is mandatory, and non-compliance may result in disciplinary action.

# Point of Sale:
Implement a thorough customer onboarding process, which includes collecting detailed information about customers, such as their employment status, credit history, and other relevant financial information. Use the logistic regression model to assess the credit risk of potential customers during the onboarding process. Set a threshold for risk tolerance and deny service to high-risk customers or require additional guarantees (e.g., security deposits, co-signers, or advance payments).

## Risk Assessment and Thresholds:

* Logistic Regression Model: 
The logistic regression model will incorporate relevant predictors of credit risk, including disconnection history, hardship history, payment delinquency history, and other credit bureau data. The model will generate a probability score between 0 and 1, representing the likelihood of a customer defaulting.

* Risk Tolerance Thresholds:

  i. Low-risk customers: Probability score between 0 and 0.1
  
  ii. Medium-risk customers: Probability score between 0.1 and 0.25
  
  iii. High-risk customers: Probability score above 0.25

* Acceptance Criteria:

  i. The company aims to maintain an annual bad debt write-off within a tolerance of 3-5%.
  
  ii. To achieve this, we will set acceptance criteria based on the logistic regression model's results and the risk tolerance thresholds:

1. Low-risk customers: Accept without additional requirements.
2. Medium-risk customers: Accept with additional requirements, such as a security deposit equivalent to two months' estimated billing or a co-signer with good credit.
3. High-risk customers: Accept only if the customer can provide a significant security deposit (e.g., three months' estimated billing) or a financially stable guarantor.

## Credit Rating Score Thresholds:

* In addition to the logistic regression model, the company will consider credit rating scores provided by credit bureaus during the customer onboarding process. The credit rating score is an industry-standard assessment of an individual's creditworthiness, with scores typically ranging from 300 to 850.

* The company will use the following credit rating score thresholds as an additional criterion for assessing customers' credit risk:

  i. Good credit rating: Score of 670 or above
  
  ii. Fair credit rating: Score between 580 and 669
  
  iii. Poor credit rating: Score below 580

* Acceptance Criteria Based on Credit Rating Score:

  i. Good credit rating: Accept without additional requirements.
  
  ii. Fair credit rating: If the customer's logistic regression probability score falls within the medium-risk range (0.1 to 0.25), accept with additional     requirements, such as a security deposit equivalent to two months' estimated billing or a co-signer with good credit.
  
  iii. Poor credit rating: If the customer's logistic regression probability score falls within the high-risk range (above 0.25), accept only if the customer can provide a significant security deposit (e.g., three months' estimated billing) or a financially stable guarantor.


# Billing and Payment:

* Segment customers based on their risk levels (low, medium, and high) using the logistic regression results.

* Implement customized billing and payment plans according to the risk levels:

  i. For low-risk customers, offer standard billing and payment options, with flexibility in payment terms.
  
  ii. For medium-risk customers, offer customized payment plans with closer monitoring and more frequent follow-ups.
  
  iii. For high-risk customers, require more frequent payments (e.g., bi-weekly or weekly) and closely monitor their accounts for potential delinquency.

* Regularly update the logistic regression model with new customer information and adjust the risk levels accordingly.

# Collections and Recovery:

* Monitor customer accounts closely for any signs of financial distress or delinquency.

* Implement a proactive collections strategy, contacting customers with overdue payments in a timely manner.

* For customers with a higher risk of default, prioritize contacting them and offer additional support, such as financial counseling or alternative payment arrangements.

* Continuously monitor the effectiveness of the collections strategy and refine it based on customer feedback and performance metrics.

# Hardship and Disconnection Management:

* Develop policies for customers experiencing financial hardship, such as offering payment extensions, deferred payments, or reduced payment plans.

* Closely monitor the accounts of customers on hardship programs and adjust their risk levels accordingly.

* For customers who have been disconnected due to non-payment, require proof of financial stability or a deposit before reconnection.

* Continuously review and refine hardship and disconnection policies to ensure they effectively mitigate bad debt write-offs while supporting customers in need.

# Data Analysis and Continuous Improvement:

* Regularly analyze the logistic regression results to identify trends and patterns in customer payment behavior.

* Use these insights to refine the risk management strategy, such as identifying additional predictors of default or adjusting the thresholds for risk levels.

* Continuously evaluate the effectiveness of the implemented processes, rules, and policies and make adjustments as needed.
By following this comprehensive approach, I would be able to manage the risk of default and bad debt write-offs throughout the customer lifecycle, ensuring the financial stability of the energy company.



