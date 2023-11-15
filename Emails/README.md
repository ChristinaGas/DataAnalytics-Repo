# Email Spam Detection

We've all been there – receiving a flood of spam emails and text messages. It's not just annoying; it can be a significant waste of time. Explore this independent project where I delved into the intriguing world of email spam detection. In this journey, I harnessed the power of machine learning and natural language processing to differentiate between spam and non-spam emails.

**Overview:**

1. **Preprocessing:** It is critical to preprocess the data in these kinds of projects. Inevitably there is a lot of noise and unprocessed content.
2. **Bag of Words Model and N-gram Model:** The Bag of Words model is a powerful tool in natural language processing. It turns text messages into binary vectors, allowing us to prepare them for machine learning algorithms. These transformed vectors set the stage for classifying emails as either spam or not. Similarly, N-gram models were used, including 1-gram and 2-gram models.
3. **Machine Learning:** To tackle the challenge of distinguishing between spam and non-spam, I trained three **Logistic Regression** models. The first had no regularization, the second utilized L1 regularization, and the third employed L2 regularization. The aim was to understand their effectiveness in spam identification, measured through F1 scores. Also, I also tuned the **Multinomial Naive Bayes classifier** with different alpha (smoothing parameter) values to improve its spam identification abilities. These models were used to both Bag of Words and N-gram models.Various hyperparameters are tuned to achieve the best classification results.
4. **Critical Words:** Curious about the most vital words in detecting spam? I dug deep into the L1 regularized logistic regression model to uncover them. 

This project on email spam detection highlights the effectiveness of machine learning and NLP techniques in tackling a common annoyance. With a focus on data preprocessing, Bag of Words, and N-gram models, it's a valuable contribution to email filtering and efficient digital communication.
