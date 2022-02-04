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
The project requires us to work on simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO(buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer. These pose challenge in analysing the data. The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.

**Data Preparation**<br>
There are three datasets provided and each dataset is cleaned and preprocessed for further analysis. The target features for analysis are offer_success, percent_success.

**File Descriptions**
Portfolio - renaming id column name to offer_id, one-hot encoding of channels and offer_type columns
Profile - profile: renaming id column name to customer_id, replacing age value 118 to nan, creating readable date format in became_member_on column, dropping rows with no gender, income, age data, converting gender values to numeric 0s and 1s, adding start year and start month columns (for further analysis)
Transcript - renaming person column name to customer_id, creating separate columns for amount and offer_id from value col, dropping transaction rows whose customer_id is not in profile:customer_id, converting time in hours to time in days, segregating offer and transaction data, finally dropping duplicates if any

File Descriptions
There is a notebook available here to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above qustions

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed
Results
The main observations of the code are published here.
