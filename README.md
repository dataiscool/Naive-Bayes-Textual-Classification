# Textual Classification on 20news dataset

In this project, I implement multinomial naive Bayes from scratch to classify the 20news dataset. Setting laplace smoothing hyperparameters to 1, the highest accuracy obtained was 84%. The LogSumExp trick was used in the predict function to avoid numerical problems (underflow).

Other notes: Pre-processing was extremely important for such a large dataset. Removal of garbage words such as non-alphabetical strings and special characters was important in increasing the accuracy of the model and speeding up the training process. Further, the use of sparse matrices was crucial in this project, which saved ram and decreased computation time.
