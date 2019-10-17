Problem Statement and Rules
Problem Statement: PredCatch Analytics' Australian banking client's profitability and reputation are being hit by fraudulent ATM transactions. They want PredCatch to help them in reducing and if possible completely eliminating such fraudulent transactions. PredCatch believes it can do the same by building a predictive model to catch such fraudulent transactions in real time and decline them. Your job as PredCatch's Data Scientist is to build this fraud detection & prevention predictive model in the first step. If successful, in the 2nd step you will have to present your solutions and explain how it works to the client. The data has been made available to you. 

The challenging part of the problem is that the data contains very few fraud instances in comparison to the overall population. To give more edge to the solution they have also collected data regarding location [geo_scores] of the transactions, their own proprietary index [Lambda_wts], on network turn around times [Qset_tats] and vulnerability qualification score [instance_scores]. As of now you don't need to understand what they mean.

Training data contains masked variables pertaining to each transaction id . Your prediction target here is 'Target' .

1: Fraudulent transactions

0: Clean transactions

You need to submit your predictions in terms of hard classes [0,1] only in csv format. Your submissions will be evaluated using cohen_kappa_score [available under sklearn metrics in Python and package Psych in R].

Higher the cohen_kappa_score, better is your model. You can decide what data and datasets to make use of during model building. Ideally if you can make use of all the data, your model may be better .

You need to build your model and make prediction for dataset 'test_share.csv'. This data doesn't contain the real 'Class' outcome. You wont be able to evaluate your model on this data. You'll need to make use of cross-validation or any other validation strategy to evaluate your model on training data itself. 

We have, at our end the real outcomes for test_share. Your predictions will be scored on the basis of comparisons against the same.

Submission File should contain only two columns: 'id' , 'Target' and be in csv format.

Rules : 

1. Since this is a hiring hackathon, it is not a team one. You are supposed to participate alone. Any kind of collaboration between participants will lead to straight disqualification. Top performers will anyways have to explain their solutions in depth.

2. You are free to use either R or Python.

3. Scores will directly be available in Leader board and it gets updated in every 10 minutes of your submissions. Kindly refresh the Leader board page to see the update. Please wait before submitting next solution until your score gets updated. If you don't see the Leader board change for an hour kindly send a mail to dipesh.bhatt@edvancer.in

4. You can submit as many times as you want. 

5. Submission should have as many observations as in the test_share.csv.

6. Your highest score amongst all submissions will be considered your final score. 

7. Top 20% participants will be required to submit their scripts and CVs for further interview rounds.

8. If your initial score is low and you are down the leaderboard don't get discouraged. Just take the time to think and try again.

Last modified: Monday, 11 March 2019, 4:30 PM
