<b>Objective</b><br>
The objective of this competition was to predict the engagement score using the given feature.<br><br>
<b>Feature Engineering</b><br>
I used Auto Feature Engineering tools to create 30 different
features, I selected 18 of them by using Rectified Feature
Elimination.
<br><br>
<b>Dealing with Skewness</b><br>
The target variable was highly skewed on the right side. I used
Box Cox transformation to transform it into a normal distribution.<br><br>
<b>Model</b><br>
I used ensembles of various LightGBM models. I tuned their
parameters using a Bayesian Optimization framework called Optuna.<br><br>
<b>Final Result</b><br>
R2-Score = 44.1<br>
Rank = 28/7500+
