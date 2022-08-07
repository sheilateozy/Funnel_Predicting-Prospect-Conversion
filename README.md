# Predicting Funnel's prospect conversion
## Using Logistic Regression, CatBoost, Random Forest, XGBoost

I worked as a Student Machine Learning Engineer at Funnel, as part of a team of 5. Our team consisted of 2 students from Columbia Engineering and 3 MBA students from Columbia Business School, coming together to tackle a real-world business problem at Funnel.
<br><br>This is the project that we worked on, which resulted in a 50% increase in successful prospect conversions.
<li> Unique modelling approach of building 1 model per stage of prospect journey.
<li>Extensive feature engineering from working with business stakeholders to obtain domain knowledge.
<li>Tailored machine learning metrics to business goals.
<li>Black-box model explanation using SHAP (SHapley Additive exPlanations).
  
# About
Funnel provides property management software whose target group are leasing agents. Leasing agents use their software to keep track of prospective renters who express interest in the properties they manage.

Our project involves creating a machine learning model that scores prospective renters in terms of their conversion rate, ie. probability of eventually renting from the leasing agent.

Prior to this project, leasing agents who use Funnel's software have no predetermined method of filtering through hundreds of new prospective renters that come in everyday, in deciding which ones are more important to follow up on. This project aims to enhance the software's capabilities by integrating this machine learning model into its system. With this, all prospective renters that express interest will be ranked by likely conversion rate and leasing agents can then prioritize them accordingly to help maximise conversion results. This increase the utility that Funnel's software provides to leasing agents.
  
# Data
This project uses 60 million records with 400+ features that contain information about properties, prospective renters, and their interactions with leasing agents.
  
# Project Methodology
1. Data exploration: Data characteristics unique to this project<br>
2. Make modelling decisions: Build 1 model per stage of prospective renter's journey<br>
3. Feature selection using Permutation Importance in a CatBoost model: 400 to 50 features
4. Feature engineering
5. Train and tune models using Bayesian Optimization: Logistic Regression, CatBoost, XGBoost
6. Obtain SHAP feature importances

# Results: Making an impact at Funnel
In total, we built 3 models that each predicts a prospective renter's conversion rate at a distinct point of their journey. The models have an ROC-AUC of 91%, 60%, and 66% respectively. This means that the first model ranks 91% of prospective renters correctly in terms of their conversion rate. This leads to:
<li>Time savings of 250 hours a year from leasing agents not having to manually go through each new prospect before deciding who to reach out to.
<li>50% increase in successful rents by leasing agents who are able to go after the most lucrative prospects from the get-go.
<li>30% increase in Funnel's software functionality thus enhancing its utility to leasing agents.
  
# Still curious?
Check out this project on my website <a href="https://sheilateozy.github.io/#portfolio" target="_blank">here</a> :)

