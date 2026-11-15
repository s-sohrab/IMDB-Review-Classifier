markdown
# 🎬 IMDB Movie Review Sentiment Classifier

A robust Deep Learning pipeline for **binary sentiment classification** of movie reviews using the IMDB dataset. This project demonstrates the end-to-end process of building, training, and evaluating a fully connected neural network for Natural Language Processing (NLP) tasks.

---

## 📌 Overview

This repository contains a complete implementation of a neural network designed to classify movie reviews as **Positive** or **Negative**. The model is trained on 25,000 highly polarized reviews and evaluated on a separate test set of 25,000 reviews. The project serves as a practical example of applying Deep Learning concepts such as One-hot encoding, ReLU activation, Sigmoid output, and Binary Cross-Entropy loss.

---

## 🏗️ Model Architecture

- **Input Layer:** 10,000-dimensional One-hot encoded vectors (representing the most frequent words).
- **Hidden Layers:** Two Dense layers with 16 units each, using **ReLU** activation for non-linearity.
- **Output Layer:** 1 unit with **Sigmoid** activation to output the probability of the review being positive.
- **Optimizer:** Adam (with SGD comparison in the notebook).
- **Loss Function:** Binary Cross-Entropy.
- **Metrics:** Accuracy.

---

## 📂 Project Structure

```text
├── notebook.ipynb        # Full training pipeline (data loading, preprocessing, model building, evaluation)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
🚀 Getting Started
Prerequisites
Ensure you have Python 3.8+ installed. Install the required dependencies using:

bash
pip install -r requirements.txt
Running the Notebook
Open notebook.ipynb in Jupyter Notebook or Google Colab to explore the full training pipeline and visualizations.

📊 Results
The model achieves approximately 88% accuracy on the validation set, demonstrating the effectiveness of a simple feedforward neural network for sentiment analysis. Detailed training curves (Loss and Accuracy) and a comparison between SGD and Adam optimizers are included in the notebook.

🧠 Key Learnings
Data Preprocessing: Handling variable-length sequences via One-hot encoding.

Regularization: Using Early Stopping and Dropout to prevent overfitting.

Optimization: Comparing the convergence speed of SGD vs. Adam.

Evaluation: Analyzing training and validation loss to detect overfitting.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
Samad Sohrab

GitHub: @s-sohrab

Field: Deep Learning & Neural Networks

This project was developed as part of a Deep Learning course presentation.
