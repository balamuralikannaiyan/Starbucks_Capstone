# Starbucks_Capstone

**Table of Contents**
1. Installation<br>
2. Project Motivation<br>
3. Data Preparation<br>
4. File Descriptions<br>
5. Results<br>

**Installation**<br>
Anaconda Distribution has most of the libraries necessary for the analysis done.<br>
Progressbar needs to be installed. <br>

**Project Motivation**<br>
The project requires us to work on simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO(buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer. These pose challenge in analysing the data. The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type<br>

Below are the three business questions that the study aims at answering:<br>
1. Number of offers received in each offer type and which of them has higher success rate<br>
2. Number of offer received in each offer id and number of them successful<br>
3. Can we predict if a customer will try to avail an offer?<br>

**Data Preparation**<br>
Data Preparation involves merging transaction and offer data. <br>
Every offer received to a customer is analysed to determine if the offer is successful(meaning that purchase is made to avail the offer) or not and all the purchase, offer and customer data is merged with each received offer. This dataset forms the base to answer the business questions. 

**File Descriptions**
The data is contained in three files inside a folder called data:
portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)<br>
profile.json - demographic data for each customer<br>
transcript.json - records for transactions, offers received, offers viewed, and offers completed<br>
Starbucks_Capstone_Notebook.ipynb - This has the entire analysis. 


**Results**<br>
The detailed study, analysis and results of the analysis are summarized [here](https://medium.com/@balamurali91/starbucks-capstone-project-cba34279466c).
