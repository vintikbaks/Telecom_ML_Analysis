# Telecom_ML_Analysis
<br>

**The goal of the analysis:**
&nbsp;&nbsp;&nbsp;&nbsp;
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp; Every business is striving to maximize the number of clients. To achieve this goal, not only is it necessary to attract new clients, but it is also important to retain the existing ones. Retaining customers is cheaper for the company than attracting new ones. Apart from that, there is already data available about the interaction of existing customers with the business.<br>

&nbsp;&nbsp;&nbsp;&nbsp; Therefore, by predicting churn rate we can try and retain customers that are about to leave in a timely manner. Relying on the collected data we can attempt to change the customer's decision to leave the carrier.<br>

&nbsp;&nbsp;&nbsp;&nbsp; The analysis includes the following points:
1. EDA *(with calculating basic statistics)*, 
2. Exploring variable relationships and forming hypotheses
3. Building models for predicting churn
4. Comparing the model quality

## Codebook
<br>

`telecom_users.csv` contains the following columns:<br><br>

&nbsp;&nbsp;&nbsp;&nbsp; `customerID` – client id<br>
&nbsp;&nbsp;&nbsp;&nbsp; `gender` – client's gender (male/female)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `SeniorCitizen` – whether the customer is a senior citizen (1, 0)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `Partner` – whether the customer is married (Yes, No)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `Dependents` – whether the customer has dependents (Yes, No)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `tenure` – the time that the customer has been with the company (in months)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `PhoneService` – whether the phone service is connected (Yes, No)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `MultipleLines` – whether the customer is using multiple phone service lines (Yes, No, No phone service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `InternetService` – client's internet provider (DSL, Fiber optic, No)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `OnlineSecurity` – whether the online security service is activated (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `OnlineBackup` – whether the online backup service is activated (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `DeviceProtection` – whether the customer has device protection insurance (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `TechSupport` – whether the customer is using tech support (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `StreamingTV` – whether the customer is using TV streaming (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `StreamingMovies` – whether the customer is using movie streaming (Yes, No, No internet service)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `Contract` – the type of the contract (Month-to-month, One year, Two year)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `PaperlessBilling` – whether the customer is using cashless payment methods (Yes, No)<br>
&nbsp;&nbsp;&nbsp;&nbsp; `PaymentMethod` – payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))<br>
&nbsp;&nbsp;&nbsp;&nbsp; `MonthlyCharges` – current monthly charges<br>
&nbsp;&nbsp;&nbsp;&nbsp; `TotalCharges` – total charges over the client's tenure<br>
&nbsp;&nbsp;&nbsp;&nbsp; `Churn` – whether the customer left (Yes or No)<br>
