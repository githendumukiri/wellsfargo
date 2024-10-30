# Wells Fargo Campus Analytics 
1.	Overview: At Wells Fargo, our data scientists play a key role in driving innovative and meaningful insights that enable our lines of business to provide a world-class experience to our stakeholders. The Campus Analytics Challenge 2021 (“Challenge”) puts you in the role of a data scientist and calls you to develop a machine learning model. The dataset is small enough that you should be able to work with it on a standard laptop.

To help get your creative juices flowing, we encourage you to explore machine learning research literature and beyond, as you may find a creative approach in other sub-fields of machine learning. 

2.	Challenge Schedule: Challenge runs according to the schedule below on https://www.mindsumo.com/contests/campus-analytics-challenge-2021 (the “Challenge Website”). 

Challenge Starts 	12:00:01 p.m. Eastern Time (“ET”) on 09/13/2021
Challenge Submission Deadline	12:00:01 p.m. ET on 10/13/2021
Submissions Judged 
10/14/2021 – 11/04/2021
Potential Finalists and Winners Notified (winning subject to verification) 	11/09/2021 (on or about)

3.	Eligibility: This Challenge is sponsored by Wells Fargo Bank, N.A. (“Sponsor” or “Wells Fargo”) for full-time or part-time students, 18 years of age or older at the time of entry, who are enrolled in any higher education degree program on campus or online at colleges or universities in the United States and District of Columbia, including students attending two- and four-year programs, technical and vocational schools, junior and community colleges, as well as graduate and professional education students (collectively “Students”). Employees of Wells Fargo or MindSumo, Inc. and their respective parents, divisions, affiliates, subsidiaries, their promotional or marketing agencies, government entities and public officials, and their immediate family members (parent, child, sibling and spouse) and persons living in the same households of each such employee (whether related or not) are not eligible. To be eligible to receive any prize, potential winners must have a valid U.S. tax identification number and meet all the eligibility requirements at the time the prize is awarded. Potential winners will be required to provide Sponsor with proof that they meet the eligibility requirements for this Challenge. Void where prohibited by law.

4.	The Challenge Background: Banks are required to report suspected vulnerable (elder and dependent adult) financial exploitation. Today, much of this activity is limited to human interaction (bankers working with customers on the phone or in person), through which bankers may pick up queues, or red flags or customers self-reporting scams or financial abuse to their financial institution. Digital payments have a degree of reported fraud and claims, with the assumption that much more unreported losses occur, especially perpetrated against older adults (60 years of age or older). As digital payments continue to expand across all demographics, research shows that older adults are showing the biggest uptick in adoption during the 2020/21 period due to the pandemic. Currently, digital payment data is not analyzed specifically under the vulnerable (elder and dependent adult) financial exploitation lens. Banks are required to report elder financial abuse but, unless a customer reports fraud and files a claim, financial abuse can go undetected and repeated fraud via digital payments can continue without the banks’ knowledge. Without detection models, a large amount of fraud is left unreported by consumers and elder and vulnerable adult populations will be at greater risk of being targeted and losing savings to fraudulent payments.

Banks need better methods to help protect elder and vulnerable adults against fraud in the digital payments landscape. Predictive modeling may also be applied in some form to alert consumers and bankers in advance of a fraud attempt and potentially pre-empt certain transactions and monetary losses. As the older adult segment continues to adopt digital technology, including digital payments, banks need better ways to predict and analyze transaction data to detect high risk payment patterns or transaction attributes that signal high risk for fraud, especially for older and vulnerable adult customers, which could be targeted by scammers.

5.	Challenge Objective: The Challenge is for you to develop a machine learning model to predict suspected elder fraud in the digital payments space as described in Rule 4. Your machine learning model (“Solution”) must meet: (a) the Challenge Criteria, (b) follow the Challenge Instructions and Requirements, and (c) incorporate the Key Deliverables, each described in detail below. 

6.	Challenge Criteria:  Build a classification model for predicting elder fraud in the digital payments space as described in Rule 4, which:
a)	handles missing variables
b)	maximizes the F1 score, 
c)	uses the given data set, 
d)	includes suitable encoding schemes, and
e)	has the least set of feature variables.

The dataset provided on the Challenge page is synthetic. Conditional GAN (“CTGAN”) was used to generate the synthetic dataset for this Challenge. CTGAN is a neural network model that helps to detect the distributions for the dataset and tries to generate data records with similar distribution compared with the original datasets. It can deal with both continuous and categorical features.

7.	Challenge Instructions and Requirements: When creating your Solution, you may use a novel combination of existing machine learning and/or statistical methods, or develop your own novel method in order to extract and/or represent thematic information from the data file. 

The output needs to include prediction of a target variable. Additionally, your Solution must meet the following requirements:
•	You must use Python 3. 
•	You must provide citations and sources.

(a)	Challenge Suggestions: You may use any clustering, dimensionality reduction, or other algorithm families. Please note that among other criteria, you will be evaluated on whether your selections of methods are appropriate for structured data.

(b)	Key Deliverables: 
 
Deliverable 1: Your results
A table of your results assigning topics to a list of dataset description identifiers in the format shown below. 

Very important note: Each solution received should ensure that the dataset_id is present in every record and arranged numerically in the same order as the testset_for_participants.csv file. The solution should also contain a column called ‘FRAUD_NONFRAUD’, which is the predicted class (either FRAUD or NONFRAUD); value of this column needs to be 0 (FRAUD) and 1 (NonFraud). If this is not the case, the submission will be automatically disqualified. 

dataset_id	FRAUD_NONFRAUD

Deliverable 2: Your method 
A description of your approach delivered as:
•	A visual description (flow chart or similar) of the path of the data through your pipeline. Note the areas where your approach is novel. 
•	A few paragraphs describing the rationale behind your method.

Deliverable 3: Your code
•	Well-commented code that is operational and can be run using the data provided and generating the output of your approach.
•	An environment configuration file that lists the names and versions of the libraries you used. 

# Results
 
              precision    recall  f1-score   support

           0     1.0000    0.9970    0.9985      1326
           1     0.9988    1.0000    0.9994      3294

    accuracy                         0.9991      4620





