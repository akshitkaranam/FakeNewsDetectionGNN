Here we harness the power of Graph Neural Networks (GNNs) for solving the problem of Fake News Detection. We utilise information regarding both the spread of fake news over twitter via propogation graphs and the user preferences via past tweets to make a prediction about the veracity of a web article.

There are 6 ipynb notebooks

1. Best_model_Politifact_default_split (splits the politifact dataset into 20:10:70) 
2. Best_model_Politifact_custom_split (splits the politifact dataset into 70:10:20)
3. Best_model_gossipcop (Only 1 model is used for this, with a default slpit of 20:10:70)
4. Politifact_Bert (Investigating the usage of ‘bert’ feature vector)
5. Politifact_Content (Investigating the usage of ‘content’ feature vector)
6. Traditional Methods for Fake News Classification

Notebooks 1,2 and 3 are used for the main models. These notebooks contain the results as reported in the report. 

Notebooks 4 and 5 see the differences between using the ‘bert’ feature vector and ‘content’ feature vector.
