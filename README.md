# Predicting Advertising Costs

An advertising company has a client who wants to predict the Advertising cost they need to spend based on target sales. The data used to predict this is as follows:
Data Sales.txt, which has 2 columns: Sales and Advertising (million $) https://www.econometrics.com/intro/sales.htm

1. Download the data from https://www.econometrics.com/intro/SALES.txt
2. Save the data locally or on Google Colab
3. Perform predictions using simple regression
4. The client wants to know the Advertising cost required if:
   a. 50 sales
   b. 100 sales
   c. 150 sales
5. Calculate the predicted advertising cost for each of these sales
6. Evaluate the predictions using RMSE and R² score
7. Interpret the results
8. Upload the results, code, and screenshots to a GitHub repository
9. Don't forget to provide a README about the repository


## Introduction
This homework aims to predict the advertising cost required to achieve a certain level of sales using simple linear regression.

## Dataset
The dataset contains two columns:
- Sales (in million $)
- Advertising (in million $)

## Methodology
A simple linear regression model was built using the Sales data to predict Advertising costs. The model's performance was evaluated using RMSE and R² score.

## Results
Predicted Advertising Costs:
- For 50 sales: $77.83 million
- For 100 sales: $173.58 million
- For 150 sales: $269.32 million

Model Evaluation:
- RMSE: 14.367119905549034
- R² Score: 0.3978668208721431

## Conclusion
The model provides a reasonable prediction of advertising costs based on sales. Further improvements could be made by incorporating additional features or using more complex models.
