Breast cancer is the most common cancer in women in India and accounts for 27% of all cancers in women . During 2012, in India, 144,937 were new cases for women for development of breast cancer in which 70,218 women died of breast cancer so if we calculate 144937 / 70218 = 2.06 which rounds off to 2. So roughly, for every 2 women newly diagnosed with breast cancer, one lady is dying of it.

There are large number of algorithms for predicting and classifying the cancer. The following code  gives the prediction of breast cancer using machine learning with help of artificial neural networks in which feed-forward and back-propagation algorithms are applied. goal is to evaluate effectiveness and efficiency of neural networks for the prediction.

Dataset based on Breast Cancer
The dataset used in this research has been taken from the UCI Machine Learning Repository, namely Wisconsin Breast Cancer (Diagnostic) dataset that was obtained by Dr. William H. Wolberg at the University of Wisconsin Madison Hospitals. 699 records have been used in this dataset. The dataset consists of nine features. These feature are classified on basis of a period scale from 0.1–1.0. Here 1.0 represents the most abnormal state. Dataset that has been used has 699 cases (Malignant: 241, Benign: 458), 2 category (34.5% benign and 65.5% malignant).

Table 1: Description of Characteristics of Wisconsin Breast Cancer Dataset. 
Characteristic Number	Description of different Characteristics	  Values
1	Thickness of Clump	0.1-1.0
2	Cell Size Uniformity 	0.1-1.0
3	Cell Shape Uniformity	0.1-1.0
4	Marginal Adhesion	0.1-1.0
5	Size of Single Epithelial cell	0.1-1.0
6	Bare Nuclei	0.1-1.0
7	Bland Chromatin	0.1-1.0
8	Normal Nucleoli	0.1-1.0
9	Mitoses	0.1-1.0

Artificial Neural Network Training and Testing
The model was analysed and trained taking 372 instances from the dataset in which the benign and malignant data is (50%-50%) to make sure there is no biasing. These 372 instances where properly mined from the dataset so that there is greater accuracy and less error. About rest 30% of the data was tested and the network predicts the accuracy up to 98%.
The model was trained with the help of a back-propagation algorithm. This help in generating sufficiently less value for MSE.The algorithm described for trainingmodifies the weights to reduce the error from the network. After the network is trained, the weights are fixed. When the trained network is tested using some testing data values then it generates the output.The trained network gives the output which is either malignant or benign. 
                                Table 2: Results of Prediction Accuracy obtained	
Model No.	Model based on Hidden Neurons	Accuracy of prediction obtained (%)
1	No. Of Neurons =10	98.9247%
2	No. Of Neurons =7	99.4624%
3	No. Of Neurons =6	97.8495%
4	No. Of Neurons =5	98.6559%
5	No. Of Neurons =4	97.8495%
The simulation experiments were performed with 372 records and 9 attributes using Wisconsin breast cancer dataset. Table 2 shown above is describing the correction prediction percentage for every model that is tested on the trained network with 100 data as testing data. From the Table 2, Results clearly specifies that model 2 has obtained the maximum percentage of correction prediction, so we have achieve that the prime neural network model is model no 2 having Hidden Neurons equal to 7. 

