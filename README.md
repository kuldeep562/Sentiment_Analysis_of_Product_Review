# 🧠 Sentiment Analysis of Product Reviews

This project uses **VADER Sentiment Analysis** from NLTK to classify product reviews into **positive**, **neutral**, or **negative** categories.

## 📌 Project Overview

We load product reviews, perform sentiment analysis, and visualize the sentiment distribution using Python tools.

## 📁 Files

- `Sentiment_Analysis_With_Extras.ipynb`: Main Jupyter Notebook
- `data/Reviews.csv`: Review data
- `requirements.txt`: Python dependencies
- `.gitignore`: Files to exclude from Git

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Sentiment-Analysis-Product-Reviews.git
   cd Sentiment-Analysis-Product-Reviews
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Sentiment_Analysis_With_Extras.ipynb
   ```

4. Make sure `data/Reviews.csv` is available in the `data/` folder.

## 🛠️ Requirements

- Python 3.7+
- See `requirements.txt` for full list

## 📈 Output

- VADER sentiment scores (`compound`, `neg`, `neu`, `pos`)
- Sentiment labels: `positive`, `neutral`, `negative`
- Visualizations using Seaborn

## 🙌 Acknowledgements

- NLTK's [VADER Sentiment Analyzer](https://github.com/cjhutto/vaderSentiment)

