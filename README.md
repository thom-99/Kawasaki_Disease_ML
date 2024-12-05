## Predicting Kawasaki Disease: A Machine Learning Approach to Transcriptomics Data

Kawasaki Disease is a syndrome of cause still unknown that mainly affects children under the age of 5. It results in a fever which can last more than 5 days that is not affected by usual medications. 

in this project my main purpose was to build a Machine Learning model that could predict wheter or not a child is affected by Kawaski Disease by analyzing their transcriptomic profile. 

in order to do that I had to:
  1) preprocess the data.
  2) perform Principal Compontent Analysis to reduce the dimensionality of the dataset.
  3) select and train a ML model on the relevant genes.

I opted for a Logistic Regression model in this instance, as it commonly used to predict diseases (or binary conditions in general).

### Limitations
unfortunately the dataset is not very large and there is a big mismatch between the number of individuals affected with kawasaki disease and the control group, this could impact the model accuracy.

### Future Plans 
  1) implement a differential expression analysis.
  2) try to search for compatible transcriptomic data from the same tissue in other healthy individuals to fit those samples in the control group and potentially improve the accuracy of the model.

  -) experiment with different ways to reduce dimensionality
