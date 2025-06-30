# Spam-Mail-Prediction
This project focuses on building a machine learning model to classify emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing techniques and classification algorithms.The model is trained using Logistic Regression for classification.The dataset obtained from Kaggle and preprocessing steps such as mapping,TF-IDF (Term Frequency–Inverse Document Frequency) vectorization were applied.
## Dataset
The dataset used for this project is from kaggle:
Email Spam Detection:https://www.kaggle.com/datasets/venky73/spam-mails-dataset/data
This dataset contains different mails labeled as Spam and Ham
## Preprocessing Steps
Before Training THe Model,following Preprocessing steps were applied:
1. Mapping-Mapped the spam and ham labels to 0 and 1
2. TfIdfVectorization-Transformed textual data into numerical representations,TF-IDF transforms text into numerical vectors that highlight important words
## Model: Logistic Regression
In this project, Logistic Regression is used to analyze TF-IDF features extracted from the message text and learn a decision boundary between spam and non-spam messages.
 About Logistic Regression
**Logistic Regression** is a supervised machine learning algorithm used for **binary classification** problems — such as predicting whether an email is **Spam (0)** or **Ham (1)**.
Logistic Regression applies the sigmoid function to produce probabilities between 0 and 1:
\[
P(y=1|x) = \frac{1}{1 + e^{-(w_0 + w_1x_1 + w_2x_2 + \ldots + w_nx_n)}}
\]
- If the probability > 0.5, it predicts **Ham** (1)
- Else, it predicts **Spam** (0)
## Results
Training Accuracy- 0.968
Testing Accuracy- 0.959
