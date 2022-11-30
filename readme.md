## About
Here we harness the power of Graph Neural Networks (GNNs) for solving the problem of Fake News Detection. We utilise information regarding both the spread of fake news over twitter via propogation graphs and the user preferences via past tweets to make a prediction about the veracity of a web article.

This fake news detection model was built as part of the coursework for CZ4032: Data Analytics and Mining. 

We also submitted this project to the Deep Learning Hackathon organised by MLDA@NTU. My team was shortlisted for the finals (15 out over 150 teams), and we were also awarded 'Most Innovative Use of NLP" award! You can visit this repository, for more information on our hackathon submission: https://github.com/DChops/PayBack

This project was exectued with 4 other group members: Dhruv, Rahul, Pratham and Louis.

## Models
There are 6 ipynb notebooks

1. Best_model_Politifact_default_split (splits the politifact dataset into 20:10:70) 
2. Best_model_Politifact_custom_split (splits the politifact dataset into 70:10:20)
3. Best_model_gossipcop (Only 1 model is used for this, with a default slpit of 20:10:70)
4. Politifact_Bert (Investigating the usage of ‘bert’ feature vector)
5. Politifact_Content (Investigating the usage of ‘content’ feature vector)
6. Traditional Methods for Fake News Classification

Notebooks 1,2 and 3 are used for the main models. These notebooks contain the results as reported in the report. 

Notebooks 4 and 5 see the differences between using the ‘bert’ feature vector and ‘content’ feature vector.
