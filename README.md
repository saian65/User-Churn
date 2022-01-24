# User-Churn
full analytical pipeline from logs to threshold determination to model training.
we solved the problem that the vast majority of people who decide to start studying online courses give it up.
Firstly, we determinied days, when users was online , then found gaps between them, next built distribution, аnd 
got threshold between 90% and 95% percentiles.
After all,we determined day when user was online last time, and labeled the sample according
to choosen threshold. Then we fitted Random Forest and got accuracy 98,4%.
