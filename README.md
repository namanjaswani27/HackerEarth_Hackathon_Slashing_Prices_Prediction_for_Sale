# HackerEarth_Hackathon_Slashing_Prices_Prediction_for_Sale
>Secured `5th` Rank in this Competition

# Problem Statement
A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists.

To not let discounts affect local artists, the company has decided to determine the **lowest price** at which a particular good can be sold. The task is to build a predictive model using Machine Learning that helps them set up a lowest-pricing model for these products.

# Approach
- `Removed skewness` from ['Demand', 'High_Cap_Price', 'Low_Cap_Price'] columns using `log transformation`
- One-Hot representation of categorical columns
- Normalizing certain numerical features
- Final Submission : Ensembling various regression models {

                                `XGBoost`,
                                
                                `Light Gradient Boosting Model`,
                                
                                `Gradient Boosting Model`}
                                
- [Didn't work] `Pseudo Labeling` on Test Set
- [Didn't work] Label Encoding of categorical features

