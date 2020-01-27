# Pima-Indians-Dataset
## Project Objective:  
 The objective of this project is to use Machine Learning methods to predict whether a person has diabetes or not, in a supervised fashion.
 
## Dataset and sources:  
The data was collected and made available by “National Institute of Diabetes and Digestive and Kidney Diseases” as part of the Pima Indians Diabetes Database. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here belong to the Pima Indian heritage (subgroup of Native Americans), and are females of ages 21 and above.

Dataset Link: https://www.kaggle.com/uciml/pima-indians-diabetes-database

## Past Usage:  

Smith,~J.~W., Everhart,~J.~E., Dickson,~W.~C., Knowler,~W.~C., & Johannes,~R.~S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In {\it Proceedings of the Symposium on Computer Applications and Medical Care} (pp. 261--265). IEEE Computer Society Press.

Results: Their ADAP algorithm makes a real-valued prediction between 0 and 1. This was transformed into a binary decision using a cutoff of 0.448. Using 576 training instances, the sensitivity and specificity of their algorithm was 76% on the remaining 192 instances.

## Software and Libraries
This project uses the following software and Python libraries:

* Python 2.7
* NumPy
* pandas
* scikit-learn
* matplotlib  
* Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.


## Conclusion:  
I applied many algorithms and extract feature importance. We got the best accuracy of 80.72% using RandomForestClassifier.After performing a lot of exploratory data analysis and we came to many conclusions. Optimizing Random Forest and Ensemble Learning can probably find a better result. 