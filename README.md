📁 CNN-LSTM_meth
📌 Overview
This folder contains the implementation of the CNN-LSTM hybrid model used in the study "A Comparative Analysis of CNN-LSTM and Random Forest for Review Sentiment Analysis". The CNN-LSTM approach combines Convolutional Neural Networks for feature extraction with Long Short-Term Memory networks for sequential modeling, aimed at improving sentiment classification performance on textual review datasets.

📂 Folder Structure
graphql
Copy
Edit
/CNN-LSTM_meth
│
├── data/                  # Preprocessed dataset files (e.g., train.csv, test.csv)
├── models/                # Saved model weights and architecture (HDF5 or .pt files)
├── outputs/               # Evaluation results, plots, and logs
├── cnn_lstm_model.py      # Main CNN-LSTM model architecture
├── train.py               # Script to train the CNN-LSTM model
├── evaluate.py            # Script to evaluate the trained model
├── preprocess.py          # Text preprocessing utilities
└── requirements.txt       # Python dependencies
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/review-sentiment-analysis.git
cd review-sentiment-analysis/CNN-LSTM_meth
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Prepare Dataset
Place your dataset (e.g., reviews.csv) into the data/ directory and run:

bash
Copy
Edit
python preprocess.py
This will generate the train and test sets needed for training.

4. Train the Model
bash
Copy
Edit
python train.py
This script trains the CNN-LSTM model and saves the trained weights in the models/ directory.

5. Evaluate the Model
bash
Copy
Edit
python evaluate.py
Evaluation metrics such as accuracy, precision, recall, F1-score, and confusion matrix will be printed and saved to outputs/.
