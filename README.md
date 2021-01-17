# Classification-of-cardiac-arrhythmia
Arrhythmia is a cardiovascular disease, which when not treated well before time could lead to
consequential health ailments in patients. So, an early diagnosis of this life-threatening disease
would help save the lives of millions of people around us.

In this study, an idea is proposed tocategorize patients into one of the given sixteen classes, 
where the first class represents the caseof normal people or those who do not have the disease and the rest fifteen classes represent ECG
records of various other types of arrhythmias. 

This study is implemented on the dataset from theUCI ML Data Repository. This data set consists of a huge amount of feature dimensions, 
which included the records of ECG signals.

These variables are reduced using dimensionality reduction techniques. To classify, various algorithms such as K-Nearest Neighbors (KNN), Logistic
Regression, Decision Tree, Random Forest, Linear SVM as well as Kernelized SVM are employed
over original data to determine the presence or absence of arrhythmias as well as to classify them
into one of the available classes. 

The accuracies are then improved by using Principal Component
Analysis (PCA) over the original dataset. The models are then evaluated and compared using their
accuracy and recall values. The results showed that on applying PCA over the data, Kernelized
SVM surpassed the other classifiers used with an accuracy rate of 80.21%.
