<h1> Outliers_Detection_and_Handling </h1>
 
An Outlier is a data-item/object that deviates significantly from the rest of the objects. They can be caused by measurement or execution errors. The analysis for outlier detection is referred to as outlier mining. There are many ways to detect the outliers, and the removal process is the data frame same as removing a data item from the panda’s data frame.<br>
<h2>Significance of outliers:</h2>
1. Outliers badly affect mean and standard deviation of the dataset. These may statistically give erroneous results.<br>
2. Most machine learning algorithms do not work well in the presence of outlier. So it is desirable to detect and remove outliers.<br>
3. Outliers are highly useful in anomaly detection like fraud detection where the fraud transactions are very different from normal transactions.<br>
<h2>1. Outlier detection using IQR</h2>
<h3>What is Interquartile Range IQR?</h3>
IQR is used to measure variability by dividing a data set into quartiles. The data is sorted in ascending order and split into 4 equal parts. Q1, Q2, Q3 called first, second and third quartiles are the values which separate the 4 equal parts.<br>
Q1 represents the 25th percentile of the data.<br>
Q2 represents the 50th percentile of the data.<br>
Q3 represents the 75th percentile of the data.<br>
