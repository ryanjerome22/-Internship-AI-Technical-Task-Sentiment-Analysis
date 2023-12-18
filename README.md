# -Internship-AI-Technical-Task-Sentiment-Analysis

Objectives
● This is to test each candidate’s unique problem solving skills which applies to the day-to-day tasks of an AI Engineer in Sprout AI Labs (SAIL)
● By doing the demo, this tests how well they can present their work with stakeholders whether in tech and non-tech.

Problem Statement
Develop a sentiment analysis model in Python to automatically determine the general sentiment expressed in a given query. The model should be capable of discerning the sentiment of customers towards a product or a situation, providing valuable insights into user experiences.

Model Used
● Logistic regression is a commonly used model in sentiment analysis for several reasons, but it's essential to note that the choice of the best model depends on various factors, including the nature of the data, the size of the dataset, and the specific requirements of the sentiment analysis task.
● Logistic regression is particularly suitable when dealing with smaller datasets, offering lower risk of overfitting. It performs well with linearly separable data and provides probabilistic outputs, offering insights into the likelihood of sentiment classes.
● Additionally, logistic regression allows for the examination of feature importance, making it a practical choice for scenarios where a simpler model is preferred. While other models, such as support vector machines and neural networks, have their merits, logistic regression's balance of interpretability and performance makes it a compelling choice for sentiment analysis tasks.

Accuracy of the Model.
Accuracy of model on training data : 97.16312056737588
Accuracy of model on testing data : 81.33333333333333

Conclusion
The model demonstrates high accuracy on the training set, suggesting that it has learned well from the provided data.
However, the slightly lower accuracy on the testing set raises concerns about overfitting.
The precision, recall, and F1-score for each sentiment class provide a more nuanced evaluation. For instance, neutral sentiment has a lower recall, indicating that the model may struggle to correctly identify instances of neutral sentiment.
Consideration should be given to the specific requirements of the sentiment analysis task. For example, if identifying negative sentiments is more critical, improvements may be needed in the model's performance for the negative class.
