# Moneyball: The Beauty of Sabermetrics
## *Sanghyun's Data Science Project Portfolio* ##

![](images/Moneyball.png)

# [Project 1: What Makes Teams Win in Baseball? (Part 1: Runs Scored)](https://github.com/shk204105/MLB_Team_RunsScored_Prediction)
<p float="left">
  <img src="images/Filtered Correlation Matrix.png" width="450" height="450">
  <img src="images/KDE plot.png" width="450" height="450">
</p>

- Started with understanding the nature of baseball.
- Filtered data features based on **Pearson correlation** (Feature selection: Filter Method).
- Analyzed a dependent variable, **Team Runs Scored (RS)**, as well as various independent variables (**OBP**, **ISO**, **HR** etc.).
- Scaled data features that have various ranges using **StandardScaler**.
- Selected best couple of data features using the **Wrapper Method: Recursive Feature Elimination (RFE)**.
- Built a multiple linear regression model with selected data attributes to predict **Team Runs Scored (RS)**.
- Built a simple linear regression model to predict **Team Runs Scored (RS)**.
- Validated both models using a **10-Fold Cross Validation** method and compared the accuracy of those two models.
- Critically analyzed the result of analysis.

# [Project 2: What Makes Teams Win in Baseball? (Part 2: Runs Allowed)](https://github.com/shk204105/MLB_Team_RunsAllowed_Prediction)
<p float="left">
  <img src="images/Filtered Correlatoin Matrix (Pitching).png" width="450" height="450">
  <img src="images/Histogram (Pitching).png" width="450" height="450">
</p>

- Started with understanding the nature of baseball.
- Detected invalid values and replaced them with predicted values using machine learning algorithm (**IterativeImputer**).
- Filtered data features based on **Pearson correlation** (Feature selection: Filter Method).
- Analyzed a dependent variable, **Team Runs Allowed (RA)**, as well as various independent variables (**ERA**, **FIP**, **WHIP** etc.).
- Scaled data features that have various ranges using **StandardScaler**.
- Selected best couple of data features using the **Wrapper Method: Recursive Feature Elimination (RFE)**.
- Built a multiple linear regression model with selected data attributes to predict **Team Runs Allowed (RA)**.
- Built a simple linear regression model to predict **Team Runs Allowed (RA)**.
- Validated both models using a **10-Fold Cross Validation** method and compared the accuracy of those two models.
- Critically analyzed the result of analysis.
