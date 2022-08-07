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
  
# Results: Making an impact at Funnel
In total, we built 3 models that each predicts a prospective renter's conversion rate at a distinct point of their journey. The models have an ROC-AUC of 91%, 60%, and 66% respectively. This means that the first model ranks 91% of prospective renters correctly in terms of their conversion rate. This leads to:<br>
<span style="font-family:Montserrat; font-weight:700; font-size:150%; color:#fab300">Time savings</span> of 250 hours a year from leasing agents having to manually go through each new prospect before deciding who to reach out to.<br>
<span style="font-family:Montserrat; font-weight:700; font-size:150%; color:#fab300">50% increase in successful rents</span> by leasing agents who are able to go after the most lucrative prospects from the get-go.<br>
<span style="font-family:Montserrat; font-weight:700; font-size:150%; color:#fab300">30% increase in Funnel's software functionality</span> thus enhancing its utility to leasing agents.



