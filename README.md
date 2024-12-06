# Overview
&emsp; Data classificaion and missing data prediction Machine Learning project by Alex Castro, Jessica Lin, and Kevin Liu
# Tools used
The project was done on python using the <b>Jupyter Notebook</b> and uses various libraries such as Numpy, Pandas, and Scikit-learn.

# Data Classification
<u>Dataset one:</u><br>
&emsp; TrainData 1 contains 3312 features with 150 samples. Testdata1 contains 3312 features with 53 samples, and there were 5 classes in this dataset. For this set, we used a <b>random forest classifier</b> and uses <b>Variance threshold</b> for feature selection. 

<u>Dataset two:</u><br>
&emsp; TrainData 2 contains 9182 features with 100 samples. Testdata2 contains 9182 features with 74 samples. There were 11 classes in this dataset. For this set, we used a <b>support vector machine</b> for classifying the data and used <b>RFE</b> for feature selection.

<u>Dataset three:</u><br>
&emsp; TrainData 3 contains 13  features with 6300 samples. Testdata3 contains 13 features with 2693 samples. There were 9 classes in this dataset. For this set, we used a <b>random forest classifier</b> for classifying the data and due to the small number of features, classification proved to be difficult and no feature selection techniques were used because it negatively impacted accuracy.

<u>Dataset four:</u><br>
&emsp; TrainData 4 contains 112 features with 2547 samples. Testdata4 contains 112 features with 1092 samples, and there were 9 classes in this dataset. For this set, we used a <b>Support vector machine</b> for classifying the data, and used <b>RFE</b> as our feature selection technique.

<u>Dataset five:</u><br>
&emsp; TrainData 5 contains 11 features with 1119 samples. Testdata5 contains 11 features with 480 samples. There were 6 classes in this dataset. This set used three classifiers: Support vector machine, KNN, and a neural network and combined the predictions.

# Missing Data
<u>Dataset one:</u><br>
&emsp; Dataset 1 contains 242 genes with 14 samples. <b>KNN imputation</b> was used to find missing values. 

<u>Dataset two:</u><br>
&emsp; Dataset 2 contains 758 genes with 50 samples. For this dataset, <b>supervised imputation</b> with a <b>decision tree</b> was used to find missing values.