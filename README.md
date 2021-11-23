# SUL-and-adversial-attack-on-credit-card-dataset
Supervised and unsupervised learning on credit card dataset for fraud detection and adversial attack.

#Description about the dataset
Link to the dataset:- https://drive.google.com/file/d/190HQFpafdcnsRQkjc95Ei5pWM3hcfkim/view?usp=sharing
This dataset is highly imbalanced with only 492 fradulent data and 280,000 plus normal data.

#Brief about the project
Since the data is highly imbalanced two approaches were carried out one supervised and other unspervised.Since it is an imbalanced data accuracy was not considered for drawing conclusions and instead F1 acore was used.
#Supervised approach for fraud detection:-
SMOTE is an oversampling technique where the synthetic samples are generated for the minority class. This algorithm helps to overcome the overfitting problem posed by random oversampling. It focuses on the feature space to generate new instances with the help of interpolation between the positive instances that lie together.<br/>
In this approach we tried to reduce data imbalance with the help of SMOTE analysis and then applied three different supervised algorithms on the dataset -
1.Logistic Regression <br/>
2.Decison Trees<br/>
3.Random Forests<br/>

#Unsupervised approach for fraud detection:-
Anomaly detection is the process of identifying unexpected items or events in data sets, which differ from the norm. And anomaly detection is often applied on unlabeled data which is known as unsupervised anomaly detection. Anomaly detection has two basic assumptions: 
<li>Anomalies only occur very rarely in the data.<br/>
<li>Their features differ from the normal instances significantly.
In this approach we adopted to anamoly detection techniques and tried three different models on the dataset -
1.Local Outlier Factor<br/>
2.Isolation Forests<br/>
3.One class SVM<br/>

