# Python Data Preprocessing with Abalone dataset

This dataset contains information about physical measurements of abalone (a type of marine snails) for predicting their age ('Rings' feature in the dataset), from other features. This project assesses the data and preprocesses it, making it useful for classification tasks. Additionally, normalization is executed in the end part. <br>

The dataset taken from [link](https://archive.ics.uci.edu/ml/datasets/abalone).

### Built with

* Google Colab

### Libraries used 
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn 
* SciPy 

### Highlights
* Summarization Statistics
* Pandas boxplot
* Seaborn violinplot
* Seaborn pairplot
* SciPy zscore function


### What is being done?
1)	Loading the dataset and exploring the features   <br>
By running basic data exploration functions, the data and the features are explored. <br>
2)	Checking for missing data <br>
By applying checks, it is found out that there are no missing values in the dataset. <br>
3)	Checking if this is a balanced dataset <br>
 By plotting the bars of number of rings against number of abalone, it is observed that the dataset is not balanced. The datapoints not evenly distributed. <br>
4)	Computing summarization statistics <br>
By implementing boxplot, it is observed that for few of all the features('Whole weight' and 'Shucked Weight'),  the range of data values is large. And by implementing violinplot, it is seen that the skew is positive for most of the features except two of them('Length' and 'Diameter').  <br>
5)	Checking for outliers <br>
 By implementing pairplot, it is observerd that there are few features with few outliers, one of them being a major one ('Height'). <br>
6)	Normalization <br>
Zscore normalization is applied on the data. By plotting two of the features and comparing the normalized and unnormalized plots, it is observed that not much change is obtained in the shape, but there is a substantial change in the axis scale. <br>
### Conclusion
*   The data does not have any missing values. So there is no need of interpolation. <br>
*   As the dataset is not balanced, more data might be needed for a confident and reliable prediction of the age of abalone from the features. <br>
*   The dataset contains few outliers. Hence the data needs further cleaning.




