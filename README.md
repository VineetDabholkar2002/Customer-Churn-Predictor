# Customer-Churn-Predictor
A end to end project with EDA done on PowerBI, which predicts if the Customer would Churn or not by using Random Forests Classifier as its model deployed on Heroku
<br>
Link to the website --> https://customerchurn-predictor.herokuapp.com/
<br>
<br>
<img src="https://user-images.githubusercontent.com/93699671/179535019-b8266899-d056-4686-921c-52a0657fcffe.png" width=70%>

## EDA using Power BI
<details>
  <summary>Click here to expand (Power BI EDA) </summary>
  
a) Home 
  <br>
  <img src="https://user-images.githubusercontent.com/93699671/179417937-f31e7566-b54f-4ef8-bcc8-58b2133228af.png" width=70%>
  

b) Customer Profile
  <br>
  <img src="https://user-images.githubusercontent.com/93699671/179517757-39e0dc8a-5184-47ec-8cb4-ceabb3fd3532.png" width=70%>

c) Customer Profile with Churn Selected
  <br>
<img src="https://user-images.githubusercontent.com/93699671/179517834-6e4f87ab-e4de-43c2-be52-9673ff31d3af.png" width=70%>
  
  
d) Churners Profile
  <br>
<img src="https://user-images.githubusercontent.com/93699671/179417974-e5d0011f-040c-424e-bca1-3e0697cb0953.png" width=70%>
  
  
e) Churn Risks for each customer (Predicted using XGBoost model)
  <br>
<img src="https://user-images.githubusercontent.com/93699671/183242005-e3168178-b1b0-47b5-ac87-8f4a49151358.png" width=70%>
  
  
f) Key Influencers
  <br>
<img src="https://user-images.githubusercontent.com/93699671/179418023-c0af30aa-dfa3-448b-a93f-67bf45760957.png" width=70%>
  
  
g) Top segments which influence Customer Churn
  <br>
<img src="https://user-images.githubusercontent.com/93699671/179418199-79a228ed-a45e-4fb8-8297-d48b65a7e06b.png" width=70%>
  
  
h) QnA
  <br>
  <img src="https://user-images.githubusercontent.com/93699671/179418156-be10f0a0-c30b-43b6-8627-4aa31c11071f.png" width=70%>
  
  
</details>


## EDA using Python 

(In Telco Customer Churn.ipynb)


## Conclusion from EDA


1. Short term contracts have higher churn rates.<br>
2. Month to month contract is more likely opted by customers but has the greatest impact on the Churn rate (increases likelihood to churn by 6.31x).<br>
3. Customers with a two yearly contract have a very low churn rate.<br>
4. People with higher tenure are very less likely to churn as compared to shorter tenure (1 year).<br>
5. The customers who pay through electronic checks have higher churn rate whereas the ones who pay through credit card have lower churn rate.<br>
6. Customers without an internet service have a very low churn rate.<br>
7. Customers who have Internet service as Fiber Optics as a service are more likely to Churn.<br>
8. Senior Citizens are more likely to churn.<br>
9. Additional features like Security, Backup, Device Protection and Tech Support make the customer less likely to churn.<br>

## Model Training Results


All the models are giving very good performance and their accuracy seems to be very close to each other with XGBoost leading in terms of performance. After applying SMOTE ENN the models performance jumps up significantly. XGBoost is giving us one of the top model performances. Hence XGBoost model was used for predicting Customer Churn. 


  <br>
  <img src="https://user-images.githubusercontent.com/93699671/183241053-29724e1c-2a26-43cb-bf5e-90187c4c491b.png" width=50%>

## Heroku Application
<details>
  <summary>Click here to expand (Website deployed on Heroku) </summary>
<br>
a) Index Page <br>
 <img src="https://user-images.githubusercontent.com/93699671/179575055-f989b57a-ebe1-4f47-a5b5-3b55d5f159d8.png" width=70%>
 
 
b) Predictions Page <br>
 <img src="https://user-images.githubusercontent.com/93699671/179575482-8bd8b908-a9ba-461d-bafa-5b5659ecfc93.png" width=70%>


 
c) Results Page <br>
 <img src="https://user-images.githubusercontent.com/93699671/179575633-03090c97-66a9-448d-bcd2-4d1f2979fd74.png" width=70%>
 
</details>
