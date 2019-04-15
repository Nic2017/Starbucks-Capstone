# Starbucks-Capstone
Capstone project of Udacity DSND 

# Installation
Make sure you have already installed library sklearn, seaborn and tqdm. Except for these, the code should run with no issues using Python versions 3.*.

# Project Motivation
For this project, given the Starbucks offer, customer profile, customer transaction data, I am going to:
1. Combine transaction, demographic and offer data to analyze which demographic groups respond(i.e.view&complete) best to which offer type;
2. Build a model that predicts whether or not someone will respond to an offer.

# File Description
There are 1 jupyter notebook file for the main analysis and 3 json files(in all_json.zip) as the input data(Starbucks offer, customer profile, customer transaction data, respectively); For convenience, I also saved and uploaded the csv files(in all_csv.zip) generated during the running of the notebook:
- **transcript_new_2.csv**: the transcript with offer id column name consolidated ((dup)rows are persons, columns are event, time, offer id, amount, reward)
- **person_and_offer.csv**: transcript_new joins portfolio((dup) adding offer info to transcript_new)
- **person_offer_demographic.csv**: person_and_offer joins parts of profile((dup) adding personal info to person_and_offer)
- **person_all_information.csv**: (nodup)rows are persons, columns are all information including offer, customer info and transaction.
- **offer.csv**: (nodup)rows are persons, columns are counts of offers received, completed, viewed&completed, noviewed&completed, received bogo,received discount, received informational, v&c_bogo, v&c_discount, v&c_discount, v&c_informational, etc.
- **offer_record.csv**: (dup)rows are persons, columns are v&c offer id and time.
- **offer_norec_comp.csv**: (nodup)rows are persons, columns are counts of offers completed, completed bogo, completed discount, completed informational, received&completed, noreceived&completed, nr&c_bogo, nr&c_discount, nr&c_informational, etc.
- **transaction_gen.csv**: (nodup)rows are persons, columns are total amount of transactions(including those not completed), amount of transactions related to viewed&completed offers, amount of transactions related to noviewed&completed offers, etc. 

# Results
For discussion 1, I have published a blog on <a href="https://medium.com/@harrygky/who-might-respond-to-starbucks-offer-f275d939bf6f">Medium</a>.

# Licensing, Authors, Acknowledgements
You can the Licensing for the data and other descriptive information is available at Udacity Data Science Nanodegree project. Otherwise, feel free to use the code here as you wish.
