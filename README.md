# Sentiment Analysis of Amazon Reviews 🛒📝📊

## Overview  

This project focuses on **sentiment analysis** using **machine learning and natural language processing (NLP)** techniques. The goal is to develop a **feedforward neural network** capable of analyzing sentiment from Amazon book reviews by leveraging **text preprocessing methods** such as **tokenization, lemmatization, and stop word removal** to enhance classification accuracy.  

## Dataset Used  

The dataset consists of **1,900+ Amazon book reviews**, labeled with sentiment scores.  
Preprocessing techniques include:  

- **Tokenization** – Splitting text into individual words for analysis.  
- **Lemmatization** – Converting words into their base form to reduce redundancy.  
- **Stop Word Removal** – Eliminating common words that do not add value to sentiment classification.  

## Project Structure  

- **notebooks/** – Jupyter notebooks for **data exploration, preprocessing, and model training**.  
- **data/** – Contains raw and preprocessed datasets.  
- **models/** – Stores serialized **feedforward neural network** models for sentiment classification.  
- **scripts/** – Python scripts for **data cleaning, training, and evaluation**.  
- **requirements.txt** – Lists project dependencies for reproducibility.  

## Setup  

1. Clone the repository:  

    ```bash
    git clone https://github.com/mzarabieh/Amazon-Sentiment-Analysis.git
    ```

2. Navigate to the project directory:  

    ```bash
    cd Amazon-Sentiment-Analysis
    ```

3. Install dependencies:  

    ```bash
    pip install -r requirements.txt
    ```

4. Train the model:  

    ```bash
    python train_model.py
    ```

5. Evaluate the model:  

    ```bash
    python evaluate_model.py
    ```

## Usage  

1. Run the Jupyter notebook `amazon_sentiment.ipynb` in the `notebooks/` folder for data analysis and model development.  
2. Use `predict.py` to classify new Amazon reviews.  
3. Evaluate the model performance using various NLP metrics.  

## Screenshots  

📊 **Sentiment Distribution**  
![](screenshots/sentiment-distribution.png)  

📖 **Word Cloud of Reviews**  
![](screenshots/word-cloud.png)  

🧠 **Model Training Performance**  
![](screenshots/model-training.png)  

---

🚀 **This project improves sentiment classification through deep learning and NLP techniques!** Let me know if you have any questions or suggestions. 😊  
