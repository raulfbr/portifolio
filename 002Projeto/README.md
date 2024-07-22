# Project 002: Default Risk Analysis in Fintech 📉

## Challenge
Investigate risk factors associated with default on personal loans using data from fintech customers. 🔎

## Tools
Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Sklearn`, `Stasmodels`, `time`, `tqdm`, `Sci-Py`) 🐍

## Methodology
CRISP-DM 🔁

## Highlights
- **Information Value (IV)**: Assessment of the predictive power of variables in relation to the target variable. 🎯
- **Exploratory Data Analysis (EDA)**: Understanding the customer profile and the distribution of defaults.
- **Data Visualization**: Use of graphs to identify patterns and trends in variables.
- **Business Insights**: Identification of risk factors and suggestions for measures to mitigate default.

## Learnings (reinforce)
- **EDA techniques**: Descriptive analysis.
- **Data Visualization with Seaborn**: pairplot, countplot.
- **Information Value Calculation**: Implementation of a custom function to calculate the IV.
- **Interpretation of Results**: Translation of analytical insights into practical actions for the business.
- *_Machine Learning:_*
> - Linear Regression (Linear Regression)
> - Logistic Regression
> - Random Forest (Random Forest)
> - Gradient Boosting
> - Neural Networks (Neural Network)

## Observation
The project demonstrates skills in risk analysis and actions to be taken to mitigate default.


---

## - **Questions to be answered**🚨
1. What is the customer profile in relation to default based on individual variables?
2. Which variables have a linear correlation and high Information Value (IV) with default?
3. What factors directly influence default, considering causality between the variables?
4. What measures should fintech adopt to minimize defaults based on the identified risk factors?
- All answers are within Notebooks, below is a summary:

## Key Insights 💡
- **Current Account Balance**: Customers with a low current account balance have a higher risk of default. 📉
- **Loan Duration**: Loans of longer duration are associated with higher default rates.
- **Sex**: Men demonstrate a significantly higher default rate than women.
- **Education and Type of Housing**: They influence the risk of default, but with less predictive power.

## Recommendations 📋
- Segment customers based on current account balance and loan duration.
- Offer customized solutions for high-risk customers, such as lower credit limits or shorter payment terms.
- Implement alert systems to identify signs of potential default.
- Invest in financial education to raise awareness among customers about the importance of responsible financial management.

## How to Contribute

To contribute:
1. Set up your development environment.
2. Clone the repository and run locally.
3. Create a branch, deploy and make a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
