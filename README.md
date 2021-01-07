# Churn Dataset
The dataset contains labeled tweets about three telco brands: Verizon, AT&T, and T-Mobile. Tweet are labeled as churny or not-churny, where churny tweets indicate a high risk of canceling the brand's service. Labels are obtained through crowdsourcing and each tweet is labeled by at least three annotators. Fleiss’ kappa is 0.62, which indicates substantial agreement among annotators. 

# Data Description

uid: user id,
tid: tweet id,
brand: name of target brand,
choose_one: label of the tweet wrt to the target brand, either "Churny" or "Non-churny", and
choose_one:confidence: a value c=<1.0 showing the aggregated confidence of the judgements

the "tids" file contains ids of all tweets in the dataset. 

Twitter developer agreement & policy doesn't allow shareing tweet content. Reach out to Hadi Amiri at hadi_amiri@uml.edu if you'd like to obtain access to the full dataset. 
 
# Publication
Hadi Amiri and Hal Daumé III, Short Text Representation for Detecting Churn in Microblogs. AAAI 2016. PDF
Hadi Amiri and Hal Daumé III, Target-dependent Churn Classification in Microblogs. AAAI 2015. PDF
