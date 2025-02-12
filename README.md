NLP News Source Classification
Project Overview:

This project focuses on classifying news article titles using a variety of machine learning models, starting from a simple baseline model to more complex approaches leveraging state-of-the-art techniques. The task aims to classify the news titles into predefined categories based on their content.

Key Models & Techniques:

Majority Class Predictor (Baseline): A simple model used as a baseline to predict the majority class in the dataset, providing a reference for comparison.

Logistic Regression with TF-IDF: Linear classification using TF-IDF vectorization of words to build a feature representation for the titles.

Word2Vec + Feed-Forward Neural Network: Leveraged word embeddings from Word2Vec and a neural network to capture semantic meanings of words in the context of news titles.

Recurrent Neural Networks (RNN) with LSTM: Captured sequential dependencies in the news titles to improve the model’s understanding of context and word order.

Convolutional Neural Networks (CNN): Applied to capture local word patterns, improving the identification of key phrases and topics in titles.
BERT (Transformer-based): A pre-trained transformer model used to leverage language representations for better performance, focusing on contextual word meaning within the titles.

Ensemble Models: Applied ensemble methods, such as Random Forest and XGBoost, to combine predictions from the best-performing models (CNN, LSTM, and BERT) to enhance accuracy and reduce overfitting.

Model Performance:

Evaluation Metrics: The performance of each model was assessed using accuracy, F1 score, precision, and recall. The models were evaluated across multiple metrics to ensure balanced performance.

Improvements: The model performance improved with each successive approach, especially as more advanced techniques were applied.
Hyperparameter Tuning: Performed hyperparameter optimization to identify the best configuration for the models, ensuring the best possible performance for each.
Final Model: The BERT-RF ensemble achieved the strongest performance across all metrics, combining the power of BERT with Random Forest to provide the best predictions.
