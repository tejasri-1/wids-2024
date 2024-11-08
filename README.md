

### [Week 1: Introduction to tools used in Machine Learning](<./Week 1/>)
This week will be a lighter one for those already familiar with Python. For those who are new, we have got you covered. 
- [Python](https://www.youtube.com/watch?v=_uQrJ0TkZlc) : Watch till 3:36:00, try to write the code and try running them, this goes for all further tutorials 
- [Numpy](https://www.youtube.com/watch?v=QUT1VHiLmmI)
- [Pandas](https://www.youtube.com/watch?v=vmEHCJofslg)
- [Matplotlib](https://www.youtube.com/watch?v=OZOOLe2imFo)



### [Week 2: Introduction to Machine Learning](<./Week 2/>)
- [Supervised Machine Learning: Regression and Classification](https://www.coursera.org/learn/machine-learning?specialization=machine-learning-introduction) - covers linear regression and logistic regression
- [Advanced Learning Algorithms](https://www.coursera.org/learn/advanced-learning-algorithms?specialization=machine-learning-introduction) -covers decision trees and neural networks.(only watch decision trees for now) 
- Apply for financial aid for these courses, and while applying, audit the course for free. Watch the videos at 2x speed; no need to complete assignments. By auditing the course, you can immediately access the videos for free without waiting for financial aid approval.
- https://www.geeksforgeeks.org/k-nearest-neighbours/ - covers knn
### [Week 3: Neural networks and more into machine learning](<./Week 3/>)
- [Advanced Learning Algorithms](https://www.coursera.org/learn/advanced-learning-algorithms?specialization=machine-learning-introduction) -covers decision trees and neural networks.(watch neural networks)
- [Developing code for machine learning algorithms](https://www.youtube.com/watch?v=i_LwzRVP7bg) - coding part
### [Week 3.2: Final Project](<./Week 3/>)
- Downlaod the dataset to begin with your Final Project,  For downloading individual files form Github use "GitZip for github" chrome extension
- Precipitation(PRCP) column in the data frame will be our target feature in this model. Replace all values greater than 0 as 1 (representing precipitation will occur), and values that are equal to 0 representing precipitation will not occur
- [Dropping null values](https://www.digitalocean.com/community/tutorials/pandas-dropna-drop-null-na-values-from-dataframe) : Drop any column that has an excessive number of null values. For the remaining columns with a lower number of null values, replace those null values with the mode of that column.
- [EDA](https://www.geeksforgeeks.org/exploratory-data-analysis-in-python/) : Perform EDA to visualize data and identify outliers
- [Data Preprocessing](https://www.geeksforgeeks.org/data-preprocessing-machine-learning-python/) : Remove outliers and find corelation matrix
- Use [SMOTE](https://medium.com/@corymaklin/synthetic-minority-over-sampling-technique-smote-7d419696b88c) to handel class imbalance : Most of the ML algorithms used for classification were designed with the assumption of an equal no. of examples in each case. Therefore we need to balance it. The imbalance has to be removed or reduced.
- Check for null values once again and proceed
- Feature selection : Feature selection will be made using the [chi-square test](https://towardsdatascience.com/chi-square-test-for-feature-selection-in-machine-learning-206b1f0b8223), refer [SelectKBest](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html#sklearn.feature_selection.SelectKBest) and [chi2](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.chi2.html#sklearn.feature_selection.chi2)
- [Normalise](https://www.geeksforgeeks.org/data-normalization-with-pandas/) the dataset
-  Training model using different techniques
   - Split data into test and train datasets.
   - Use logistic regression classifier, decision tree classifier, neural networks training dataset.
   - Calculate accuracy, precision, recall, F-1 score, and ROC_AUC on the test dataset and visualize it.
   - Plot confusion matrix using sklearn.
   - Kindly refer to the documentation provided on Google to perform the above steps
- Model Comparison : Compare models based on accuracy and ROC_AUC score and visualize it using seaborn
  

  




 


