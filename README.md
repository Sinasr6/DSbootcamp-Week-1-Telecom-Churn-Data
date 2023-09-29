# DSbootcamp-Week-1-Telecom-Churn-Data
 In this project I imagine I'm working with a telecommunication company. They're really keen on figuring out how many customers might decide to leave them in the coming months. Luckily, they've got a bunch of past data about when customers have left before, as well as info about who these customers are, what they've bought, and other things like that. So, I will be using the Telco Customer Churn dataset (https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data).

 Each row represents a customer, each column contains customer’s attributes described on the column Metadata.
I used RapidMiner for preprocessing. The only feature containnig None is TotalCharge and do to its nature, I use Mean to replace the None value.
![1](https://github.com/Sinasr6/DSbootcamp-Week-1-Telecom-Churn-Data/assets/143876385/50f20409-4080-4c0e-a32c-c562ee5fc661)

I also take care of the nominal columns for the models.
![image](https://github.com/Sinasr6/DSbootcamp-Week-1-Telecom-Churn-Data/assets/143876385/e456f0d6-ce92-4f58-a7b7-ab319b632b21)

Now I have a usable dataset.
![image](https://github.com/Sinasr6/DSbootcamp-Week-1-Telecom-Churn-Data/assets/143876385/23684be9-834c-419d-8723-7762560cdb17)

Three models of KNN, Naive Bayes and Binary Regression were attempted. 
Bellow is sample life cycle approach to this problem.

[Week One Project.pdf](https://github.com/Sinasr6/DSbootcamp-Week-1-Telecom-Churn-Data/files/12763312/Week.One.Project.pdf)
