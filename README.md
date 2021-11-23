# SUL-and-adversial-attack-on-credit-card-dataset
Supervised and unsupervised learning on credit card dataset for fraud detection and adversial attack.

# Description about the dataset
Link to the dataset:- https://drive.google.com/file/d/190HQFpafdcnsRQkjc95Ei5pWM3hcfkim/view?usp=sharing<br/>
This dataset is highly imbalanced with only 492 fradulent data and 280,000 plus normal data.

# Brief about the project
Since the data is highly imbalanced two approaches were carried out one supervised and other unspervised.Since it is an imbalanced data accuracy was not considered for drawing conclusions and instead F1 acore was used.
# Supervised approach for fraud detection:-
SMOTE is an oversampling technique where the synthetic samples are generated for the minority class. This algorithm helps to overcome the overfitting problem posed by random oversampling. It focuses on the feature space to generate new instances with the help of interpolation between the positive instances that lie together.<br/>
In this approach we tried to reduce data imbalance with the help of SMOTE analysis and then applied three different supervised algorithms on the dataset -<br/>
1.Logistic Regression <br/>
2.Decison Trees<br/>
3.Random Forests<br/>

# Unsupervised approach for fraud detection:-
Anomaly detection is the process of identifying unexpected items or events in data sets, which differ from the norm. And anomaly detection is often applied on unlabeled data which is known as unsupervised anomaly detection. Anomaly detection has two basic assumptions: 
<li>Anomalies only occur very rarely in the data.<br/>
<li>Their features differ from the normal instances significantly.<br/>
In this approach we adopted to anamoly detection techniques and tried three different models on the dataset -<br/>
1.Local Outlier Factor<br/>
2.Isolation Forests<br/>
3.One class SVM
  
# Adversial attack on credit card dataset:-
  
An adversarial attack is a method to generate adversarial examples. Hence, an adversarial example is an input to a machine learning model that is purposely designed to cause a model to make a mistake in its predictions despite resembling a valid input to a human.
Mostly this attack is done on image recognition, where modifications are performed on images that cause a classifier to produce incorrect predictions.<br/>
Here we tried this adversial sampling on credicard dataset to fool the machin learning algorithm to make wrong predictions and make the model predict fraud data as normal which in real time would be a threat to the users<br/>
We applied the Fast Gradient Sign Method (FGSM). FGSM is to add the noise (not random noise) whose direction is the same as the gradient of the cost function with respect to the data. The noise is scaled by epsilon, which is usually constrained to be a small number via max norm. The magnitude of gradient does not matter in this formula, but the direction (+/-) does.


  

