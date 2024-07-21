# Financial News Sentiment Analysis

This project focuses on sentiment analysis of financial news using natural language processing (NLP) techniques. The goal is to classify financial news articles into three sentiment categories: positive, neutral, and negative.

## Project Description

Financial news sentiment analysis is crucial for understanding market trends and making informed investment decisions. This project uses a fine-tuned BERT model to classify the sentiment of financial news articles.

## Methodology

1. **Data Preprocessing**: 
    - Load and clean the dataset.
    - Convert sentiment labels to numeric values.
    - Clean text using BeautifulSoup and regular expressions.
2. **Data Splitting**: 
    - Split the data into training and testing sets.
3. **Model Fine-tuning**: 
    - Tokenize text data using `BertTokenizer`.
    - Create a custom dataset class.
    - Define training arguments and metrics.
    - Fine-tune the BERT model using the `Trainer` class from the Hugging Face Transformers library.
4. **Model Evaluation**: 
    - Evaluate the model using accuracy, precision, recall, and F1 score.
5. **Visualization**: 
    - Visualize training accuracy and loss.
6. **Model Saving and Testing**: 
    - Save the fine-tuned model.
    - Load the model and make predictions on new data.

## Dataset

The dataset used for this project is available on Kaggle: [Sentiment Analysis for Financial News](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news).

## Setup and Environment

To set up the environment and install the required dependencies, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Mody-Medhat/Financial-News-Sentiment-Analysis.git
    cd Financial-News-Sentiment-Analysis
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
