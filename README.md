# Fake-News-Detection-Python

## Project Overview
This project is designed to detect fake news using Python and supervised learning techniques. The aim is to classify news articles as either "Real" or "Fake" using machine learning models. The dataset used includes features like article titles and text, with labels indicating the authenticity of the news.

## Features
- **Text classification** using Naive Bayes and Passive Aggressive Classifier.
- **Feature extraction** with CountVectorizer and TfidfVectorizer.
- Evaluation of model performance with **accuracy scores** and **confusion matrices**.

## Dataset
The dataset used for this project is from Kaggle, containing news articles with the following attributes:
- **Title**: The title of the news article.
- **Text**: The full text of the article.
- **Label**: Whether the news is 'Real' or 'Fake'.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Fake-News-Detection-Python.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Fake-News-Detection-Python
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Load and preprocess the data**:
   - Import the dataset (`fake_or_real_news.csv`) and split it into training and testing sets.
   
2. **Run the classifiers**:
   - Use **Naive Bayes** and **Passive Aggressive Classifier** to classify news articles.
   
3. **Evaluate the models**:
   - Generate accuracy scores and confusion matrices to assess the models' performance.
  
## Models
- **Naive Bayes Classifier**: Best suited for text classification, leveraging the frequency of words.
- **Passive Aggressive Classifier**: Ideal for large datasets, this model updates the decision boundary as new data comes in.

## Results
- **Naive Bayes Accuracy**: ~85%
- **Passive Aggressive Accuracy**: ~88%
- Confusion matrices visualize the performance and types of errors made by the classifiers.
