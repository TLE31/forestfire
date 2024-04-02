The script aims to create a predictive model that can help prevent or mitigate forest fires by identifying patterns 
and factors associated with fire outbreaks

1. Data Exploration and Visualization: The script starts by loading a dataset named ‘covtype.csv’. 
It explores the data, visualizes it using histograms and boxplots, and creates a correlation heatmap

2. Understanding the data is crucial for building an effective prediction model.
Feature Selection: The script uses the ExtraTreesClassifier to select important features.
By identifying relevant variables, it aims to improve prediction accuracy.

Model Training and Evaluation: 
The Random 3. Forest Classifier is applied to train the model on the dataset.
The goal is to predict forest fire occurrences based on input features. The model’s performance is evaluated using accuracy and a confusion matrix.
