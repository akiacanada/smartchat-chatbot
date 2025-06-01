# SmartChat Chatbot

This project uses two conversational datasets from Kaggle to train a simple chatbot model using deep learning (TensorFlow and Keras).

## Description

SmartChat is a simple chatbot prototype built on deep learning. The project demonstrates:
- Data loading and preprocessing
- Tokenization and sequence padding
- Building and training an LSTM-based model
- Evaluation and testing

## Datasets

Due to size constraints, the datasets are not included in this repository.  
Please download them manually from the following sources:

- [Simple Dialogs for Chatbot](https://www.kaggle.com/datasets/grafstor/simple-dialogs-for-chatbot)
- [Chatbot Dataset](https://www.kaggle.com/datasets/niraliivaghani/chatbot-dataset)

After downloading, place the data files in a `data/` directory like this:


smartchat-chatbot/
│── data/
│ ├── simple-dialogs.csv
│ └── chatbot-intents.csv
│── SmartChat.ipynb
│── README.md
│── requirements.txt


## Technologies Used

- Python
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- nltk
- scikit-learn
- TensorFlow

## Installation

1. Clone this repository:
   '''bash
   git clone https://github.com/yourusername/smartchat-chatbot.git
   cd smartchat-chatbot
2. Install the required Python packages:
  pip install -r requirements.txt

3. Download the datasets (see Data section above) and place them in the data/ directory.

## How to Run

1. Launch Jupyter Notebook:
  jupyter notebook

2. Open the SmartChat.ipynb notebook.

3. Follow the code cells to train and evaluate the chatbot.

## Notes
- The notebook uses TensorFlow’s Keras API for building the LSTM model.

- The random seeds are set for reproducibility.

## License
This project is open source and available under the MIT License.
