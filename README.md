<div align="center">
  <h1>Spam & Ham SMS Classifier</h1>
  <img width="480" height="280" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/8b59b9dc-366e-4459-bcc2-d818238bf033">
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

---

## Visual Workflow

<div align="center">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/e8c83f0d-95b8-482f-81f2-f75effb7e7dc">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/cc630b86-55d7-4b37-aa8e-40eed385f680">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/652fd612-63b0-4e6e-aa5e-398597578674">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/c6b5a4ec-994e-48e5-a4d5-b3a9a7a26838">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/ed0cf225-3aa8-4a84-8c52-adc8001dcde4">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/fb9f3ed9-9183-4aa9-a427-e658582d0aaf">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/f8388a82-95ec-4ed1-8102-65a8171ce54a">
  <img width="360" height="228" src="https://github.com/hitkalariya/Spam-and-Ham-text-classifier/assets/73955220/d555ce8a-be45-44ba-98a6-731de3cbbd47">
</div>

---

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
