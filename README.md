# IMDB Movie Review Classifier

A deep learning model for binary sentiment classification of movie reviews using the IMDB dataset.

## Project Structure
- `notebook.ipynb`: Full training pipeline (data loading, preprocessing, model building, evaluation).
- `app.py`: Interactive Gradio interface for real-time prediction.
- `requirements.txt`: Dependencies.

## Model Architecture
- Embedding/One-hot representation (10,000 dimensions)
- Two hidden layers (16 units, ReLU activation)
- Output layer (1 unit, Sigmoid activation)
- Optimizer: SGD / Adam
- Loss: Binary Cross-Entropy

## How to Run
Visit the live demo on Hugging Face Spaces.
