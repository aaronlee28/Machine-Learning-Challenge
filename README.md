# machine-learning-challenge

Project Overview

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar systems. 

The goal of this project is to find out which models have the best scores in terms of precision, recall, and f1-score. 

Libraries: 
Pandas 
Scikit Learn 
Tensorflow 

Process: 
Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.
Use GridSearch to tune model parameters.


Results: 

List<String> headersList = Arrays.asList("Models", "Accuracy", "Others");
List<List<String>> rowsList = Arrays.asList(
        Arrays.asList("Support Vector Machine","0.9", "-",),
        Arrays.asList("Random Forests","0.91", "-"),
        Arrays.asList("Logistic Regression","0.88", "-"),
        Arrays.asList("KNN","0.82", "-"),
        Arrays.asList("Decision Tree","0.86", "-"),
        Arrays.asList("Deep Learning", "0.89","Loss: 0.2626",)
   

Findings: 
Of the 6 models, Random Forests has the highest accuracy among all with 0.91. All of the models except for the KNN would be a great model to predict new exoplanets, because KNN has a fairly lower score compared to the other models. I am certain that deep learning would be better than SVM given that it has data and density added to the model. 






