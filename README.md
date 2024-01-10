# Zero-Day-Attack-Prediction-ML-model
Hello Guys, this is a git repo containing the project I worked on during my internship program. The goal is to create e ML model and deploy it on AWS

So What is Zero Day Attack?
- Zero Day Attack is a type of attack on a software system where a devloper has 0 seconds to prevent the attack. The attackers takes advantag of the weak portion of code of software and exploit those vulnerabilities.

Ways the code is built or model is trained!!

First step was to obtain a Datasset on which the ML model would be trained and tested. For this project I used a dataset provided by University of Brinswick which is a Canadian Institute for Cybersecurity.
Link --> https://www.unb.ca/cic/datasets/ids-2017.html

Next, after getting the Dataset data cleaning was to be done. For this process the entropy of every column was calculated. Columns having entropy zero were dropped. The rows containing NaN (Not a Number), Positive Infinity and Negative Infinity were also deleted.

We had datasets of one whole week so, combined the 6 datasets and kept one of them for training dataset

Now the dataset was trained and tested and the accuracy score and confusion matrix was used to determine the best model.
