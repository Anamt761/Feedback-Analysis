
# Feedback Analysis Classification

This project focuses on classifying feedback in college teaching and education using both Machine Learning and Deep Learning models.

## Features

- **Preprocessing**
  - Stopword removal, tokenization, lemmatization, normalization.
  - Removal of digits, special characters, and punctuation.

- **Feature Extraction**
  - TF-IDF for Machine Learning models.
  - FastText embeddings for Deep Learning models.

- **Model Training & Evaluation**
  - **Machine Learning Models:** SVM, Decision Tree, Random Forest.
  - **Deep Learning Models:** GRU, Bi-GRU (trained for 100 epochs).
  - **Performance Metrics:** Classification Report, Confusion Matrix, AUC-ROC Curve.
  - **Visualizations:** Accuracy & Loss Graphs over epochs.

## Dataset

- The dataset contains two columns:
  - `comment`: Textual feedback from students.
  - `quality`: Labels representing the quality of feedback (`Awesome`, `Good`, `Average`, `Poor`, `Awful`).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Feedback-Analysis.git
   cd Feedback-Analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Run the Jupyter Notebook `Feedback_Analysis_Classification.ipynb` to train and evaluate models.

## Results

- The notebook computes classification reports, confusion matrices, and AUC-ROC curves.
- Accuracy and loss graphs are generated for Deep Learning models.

## Contribution

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the MIT License.
