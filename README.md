🛠️ Mini Project: Email Spam Detection using Bernoulli Distribution + Logistic Regression
🎯 Objective:
Predict whether an email is spam (1) or not spam (0) using simple features.

📍 Why Bernoulli?
Logistic Regression models the probability of a binary outcome:

𝑃
(
𝑌
=
1
∣
𝑋
)
=
1
1
+
𝑒
−
(
𝛽
0
+
𝛽
1
𝑥
1
+
𝛽
2
𝑥
2
+
.
.
.
)
P(Y=1∣X)= 
1+e 
−(β 
0
​
 +β 
1
​
 x 
1
​
 +β 
2
​
 x 
2
​
 +...)
 
1
​
 
The output is interpreted as Bernoulli probability.

If 
𝑃
(
𝑌
=
1
∣
𝑋
)
=
0.8
P(Y=1∣X)=0.8, it means 80% chance of spam.

The actual target values are Bernoulli-distributed: only 0 or 1.
