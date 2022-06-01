# TelecomChurnAnalysis
<h2>Analysing over 3000 rows of data of Orange S.A. which is is a French multinational telecommunications corporation, giving a recommendation to ensure customer retention</h2>
This project include 2 file one is python executable file and other is power poin presentation file.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<!-- Steps Involved -->
<h2 id="Steps Involved"> :scroll: Steps Involved</h2>

<h2>1. Viewing and understanding the data</h2>:
In this step we use command like **df.head(), df.tail(), df.info(), df.describe(), df.shape** this will give an overview for the data, what the columns are.

<h2>2. Outlier Handling</h2>:
An outlier is an observation that lies an abnormal distance from other values in a random sample from a population.This involves two steps first is outliers detection and the second is outliers handling. For outliers detection, we have used Box-plot and for handling we have used IQR method .
<h3>Box-plot</h3>: it contains of wiskers at the end the points which are outside this two wiskers are the outliers present in the data.
<h3>IQR</h3> IQR stands for Inter Quantile Range steps involed in IQR are 
Sort the dataset in ascending order
calculate the 1st and 3rd quartiles(Q1, Q3)
compute IQR=Q3-Q1
compute lower bound = (Q1–1.5*IQR), upper bound = (Q3+1.5*IQR)
loop through the values of the dataset and check for those who fall below the lower bound and above the upper bound and mark them as outliers

<h2>3. Single Variant analysis</h2>:
A single variant analysis gives a deeper sense of that data column, it gives the distribution of the column, mean,standard deviation, and it explains the variance present in the column.

<h2>4. BI-Variant analysis</h2>:
In Bi-variant analysis we check all the independent variables agains the dependent (Target Variable).

<h2>4. Multi-Variant analysis</h2>:
In multi-variant analysis we combine two or more independent columns using group by against the target column.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Mitesh Bhanushali > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast
