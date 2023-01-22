# Machine-learning-project:



Classification:
1.	Data set: Gender Recognition by Voice: https://www.kaggle.com/primaryobjects/voicegender 


2.	Description: this data contains values for the voice through it we can predict if the person is Male or female. Contains 20 feature (columns) and only one Target which name is (Label). It also has 3166 row or data records. Features name are not clear so after reading description of the data I found that: 
A.	meanfreq is mean frequency (in kHz)
B.	 sd is standard deviation of frequency
C.	 median is median frequency (in kHz)
D.	 Q25 is first quantile (in kHz)
E.	 Q75 is third quantile (in kHz)
F.	 IQR is interquantile range (in kHz)
G.	 skew is skewness (see note in specprop description)
H.	 kurt is kurtosis (see note in specprop description)
I.	 sp.ent is spectral entropy
J.	 sfm is spectral flatness
K.	 mode is mode frequency
L.	 centroid is frequency centroid (see specprop)
M.	 peakf is peak frequency (frequency with highest energy)
N.	 meanfun is average of fundamental frequency measured across acoustic signal
O.	 minfun is minimum fundamental frequency measured across acoustic signal
P.	 maxfun is maximum fundamental frequency measured across acoustic signal
Q.	 meandom is average of dominant frequency measured across acoustic signal
R.	 mindom is minimum of dominant frequency measured across acoustic signal
S.	 maxdom is maximum of dominant frequency measured across acoustic signal
T.	 dfrange is range of dominant frequency measured across acoustic signal
U.	 modindx is modulation index. Calculated as the accumulated absolute difference between adjacent measurements of fundamental frequencies divided by the frequency range
V.	 label is male or female


3.	Data Preprocessing:
a.	Check if there are any null’s in the data to drop it but there are no nulls
b.	Check if there are any duplicates in the data, found two and has been dropped
c.	Remove the outliers






4.	  Visualizations: using heat map to identify the values in every class according to correlation.

 
5.	Confusion Matrix (decision tree classifier): This matrix represents the performance of the decision tree classifier, each row in a confusion matrix represents an actual class, while each column represents a predicted class.







6.	Learning curve according to the decision Tree: it represent the gap between learning and testing curve, it represent the accuracy.


















7.	Confusion Matrix (KNN classifier):








8.	KKN plot: to identify the testing accuracy with the value of K for Knn. 
9.	Learning curve according to the KNN:






 



















10.	Confusion Matrix (Random forest classifier):









11.	Classification report (Random forest classifier):





12.	Learning curve according to the Random forest:











	
Regression data set:
1.	Data set: Bias correction of numerical prediction model temperature forecast Data Set: https://archive.ics.uci.edu/ml/datasets/Bias+correction+of+numerical+prediction+model+temperature+forecast# 
2.	Data description: This data is for the purpose of bias correction of next-day maximum and minimum air temperatures; it contains 7752 rows and 25 columns (features).
3.	Data Preprocessing: 
a.	Check if there any null values in the data and drop it
b.	Check if there any duplicate values in the data and remove it
c.	Divide the data into two classes to be a binary classification
4.	Visualizations:
a.	Find which feature in the data set effect the result’s using the feature selection






b.	Using the heat map to classify every value in classes according to correlation:
 
c.	Data shape according to :LDAPS_LH and Solar radiation 
d.	Data shape according to: DEM and LDAPS_LH:
 
e.	Data shape according to: DEM and Solar radiation:
 
f.	Gradient Descent:









g.	LinearRegression:
















	

