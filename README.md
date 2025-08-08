<div align="center">
  <h1>Spam & Ham SMS Classifier</h1>
</div>

## Overview

This project is an end-to-end solution for classifying SMS messages as spam or ham (not spam) using a Long Short-Term Memory (LSTM) neural network. The model is trained on a labeled dataset and can be used to automatically filter unwanted messages.

---

## Project Workflow

1. **Data Collection & Preparation**
    - Download a labeled SMS dataset (link provided in the notebook).
    - Split the data into training and testing sets.

2. **Text Preprocessing**
    - Clean and tokenize SMS messages.
    - Convert text to lowercase, remove punctuation, and optionally remove stopwords.
    - (Optional) Apply stemming or lemmatization.

3. **Word Embedding**
    - Transform words into dense vectors using embeddings (e.g., Word2Vec, GloVe, or Keras Embedding layer).

4. **Sequence Padding**
    - Pad or truncate message sequences to a fixed length for LSTM input compatibility.

5. **Model Building**
    - Design an LSTM-based neural network for binary classification.
    - Use a sigmoid-activated dense output layer for spam/ham prediction.

6. **Training**
    - Train the model using binary cross-entropy loss and an optimizer like Adam.
    - Monitor performance and tune hyperparameters as needed.

7. **Evaluation**
    - Assess the model using accuracy, precision, recall, and F1-score on the test set.

8. **Deployment**
    - Integrate the trained model into an application to classify new SMS messages in real time.

## How to Run

1. Open the `SMS Text Classification.ipynb` notebook in Jupyter or VS Code.
2. Run all cells in order. The dataset will be downloaded automatically.
3. Follow the notebook instructions to train, evaluate, and test the model.

---

## Author

**Hit Kalariya**  
Email: [hitkalariya88@gmail.com](mailto:hitkalariya88@gmail.com)  
GitHub: [hitkalariya](https://github.com/hitkalariya)  
LinkedIn: [hitkalariya](https://www.linkedin.com/in/hitkalariya/)

---

## License

This project is open source and available under the MIT License.
