1. Project Title
IMDB Movie Review Sentiment Analysis Using LSTM
________________________________________
2. Overview / Description
This project addresses the problem of sentiment classification in natural language text by predicting whether a movie review expresses a positive or negative sentiment. Sentiment analysis is an important task in Natural Language Processing (NLP) with applications in recommendation systems, customer feedback analysis, and social media monitoring. The project uses a Long Short-Term Memory (LSTM) deep learning model implemented in TensorFlow/Keras to capture sequential dependencies in text data. The trained model achieves approximately 88–92% accuracy on unseen IMDB movie reviews.
________________________________________
3. Features / Contributions
•End-to-end NLP preprocessing pipeline (tokenization and padding)
•Binary sentiment classification using LSTM neural network
•Learned word embeddings for semantic representation
•Clean and modular project structure suitable for research and submission
•Model evaluation using accuracy and validation metrics
•Prediction (inference) on unseen sample reviews

________________________________________
4. Project Structure
IMDB-Reviews-Sentiment-Analysis-LSTM-project/
│
├── .idea/
│
├── data/
│   └── imdb_dataset.csv
│
├── models/
│   └── imdb_lstm_model.h5
│
├── results/
│   ├── accuracy_loss_plot.png
│   └── confusion_matrix.png
│
├── imdb_lstm_sentiment_analysis.ipynb
│
├── README.md
│
└── requirements.txt

________________________________________
5. Dataset
•Dataset Source: IMDB Movie Reviews Dataset from kaggle.com
•Dataset Size: 50,000 reviews
•Classes: Positive (1), Negative (0)
•Distribution: Balanced dataset

Preprocessing Steps:
•Sentiment label encoding
•Tokenization of text data
•Padding sequences to a fixed length
________________________________________
6. Model Architecture
•Embedding Layer (Vocabulary size: 10,000, Dimension: 128)
•LSTM Layer (128 hidden units)
•Dense Output Layer (Sigmoid activation)

Training Configuration:
•Loss Function: Binary Crossentropy
•Optimizer: Adam
•Evaluation Metric: Accuracy
________________________________________
7. Installation
1.Clone the repository
2.Install dependencies using requirements.txt
________________________________________
8. Training the Model
•Epochs: 5
•Batch Size: 128
•Validation Split: 20%
•Hardware: CPU (GPU optional)

Training is performed using a Jupyter Notebook.
________________________________________
9. Results
•Test Accuracy: 0.8941
•Test Loss: 0.3287
•Includes accuracy/loss plots and confusion matrix
________________________________________
10. Experiments
•Different sequence lengths
•Embedding dimension variations
•LSTM hidden unit tuning
•Validation split experiments
________________________________________
11. Future Work
•Bidirectional LSTM
•Attention mechanism
•Pretrained embeddings (GloVe, Word2Vec)
•Web or API deployment
________________________________________
12. Citation
Author, IMDB Movie Review Sentiment Analysis Using LSTM, 2026.
________________________________________
13. License
MIT License. This project is intended for academic and educational purposes.

