# Simple Chatbot using NLP Frameworks

## Project Overview
This project is a basic chatbot created as part of a Data Science and Machine Learning course from CipherSchools. It serves as a learning exercise to explore the implementation of Natural Language Processing (NLP) frameworks. The chatbot is designed to answer a limited set of questions, using a small custom dataset. The project includes both a Jupyter Notebook file for model building and experimentation, as well as a standalone Python app for running the chatbot.

## Features
- **Chatbot**: A simple question-answering chatbot with a predefined dataset of possible questions.
- **NLP Frameworks**: Leveraged basic NLP techniques to process and respond to user input.
- **Python App**: A Python script that runs the chatbot for user interaction.
- **Dataset**: Contains a limited set of questions and answers for demonstration purposes.

## Repository Structure
```
.
├── chatbot_dataset.csv    # Dataset used for training the chatbot
├── Chatbot.ipynb          # Jupyter Notebook with NLP model and chatbot implementation
├── Chatbot_app.py         # Python script for running the chatbot
├── README.md              # Project documentation
└── requirements.txt       # Required libraries
```

## Getting Started

### Prerequisites
Ensure you have Python installed on your machine. You can install the required libraries using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

### Libraries Used
- **Python 3.8+**
- **Jupyter Notebook**: For prototyping and developing the chatbot.
- **Pandas**: For handling the dataset.
- **NLTK (Natural Language Toolkit)**: For tokenization and text processing.
- **Scikit-learn**: For implementing the machine learning tasks
- **Dash**: For building a simple layout for chatbot
  
### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/rHarsh-11/CipherSchools-Chatbot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CipherSchools-Chatbot
   ```
3. To run the chatbot in the Jupyter Notebook, start the notebook:
   ```bash
   jupyter notebook
   ```
   Open the notebook file and run all cells.
   
4. To run the chatbot from the Python script:
   ```bash
   python chatbot_app.py
   ```

### Dataset
The dataset used for the chatbot contains a small set of questions and corresponding answers. This dataset is located in the `data/` folder and is used to train and test the chatbot.

The chatbot can only respond to a predefined set of questions, such as:
- What is your name?
- How can I help you?
- Where are you located?

## Project Details

### Chatbot Flow
1. **Data Preprocessing**: Input text is tokenized, and stopwords are removed.
2. **NLP Model**: Simple rule-based or machine learning-based text matching technique is used to match user queries to predefined responses.
3. **Response Generation**: Based on the closest match, the chatbot generates an appropriate response.


## Insights & Improvements
- The current chatbot uses a very small dataset and answers only a limited set of questions.
- Future improvements could include expanding the dataset and implementing more sophisticated NLP models such as transformers or RNNs.

## Conclusion
This project demonstrates a basic implementation of a chatbot using NLP frameworks. It's a simple, yet practical, starting point for learning how to build chatbots and integrate natural language processing techniques.

## Acknowledgements
- Dataset created manually for the chatbot.
- Inspiration from online tutorials on chatbot development and NLP.
