# Housing-Prices-Regression
Following the steps from the Hands-on Machine Learning 2 book, I understood and re-implemented this project, 
which is basically a thorough pass on what a usual Machine Learning Project is like.

1) Data understanding and quick visualization.

  -Understanding the data I will deal with and its types
  
  -Visualize the data quickly if needed
  
2) Data cleaning & preparation

  -Create a pipeline for numerical attributes
  
     -May Add/Remove Attributes
     
     -Fill/Disregard Attributes with missing data
     
     -Scale the data (Normalization or Standardization)
     
     (May be more if needed)
     
  -Create a pipeline for categorical attributes
  
     -May change them to onehot encoding
     
     -May change replace them with representative numerical values
     
     -May Add/Remove Attributes
     
  -Create a ColumnTransformer to send appropriate columns to their pipelines
  
3) Select and train models and shortlist a few

4) Evaluate the models using validation sets

5) Fine-tune the Model

  -Using GridSearchCV I can easily tune the hyperparameters to given parameters
  
  -Using RandomizedSearchCV I can easily tune the hyperparameters by trying random parameters
  
6) Check the importances of attributes in the best estimator

  -Might need to delete un-important attributes
  
7) Evaluate the model on the test set!

   
