# 📊 Amazon Product Reviews Dataset

This dataset contains over **568,000 consumer reviews** for various products listed on **Amazon.com**.

It is intended for use in **sentiment analysis**, **product feedback mining**, and **natural language processing** tasks.

---

## 📁 Dataset Details

- **Total Records:** 568,454
- **Total Columns:** 10
- **File Format:** CSV
- **Source Domain:** [amazon.com](https://www.amazon.com)

## 📥 Download Dataset

Due to size limits, the dataset is not included here.  
Please download it manually from [Kaggle](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews)  
and place it inside the `data/` folder as `sample_reviews.csv`.

---

## 📌 Columns Explained

| Column Name              | Description                                                 |
|--------------------------|-------------------------------------------------------------|
| `Id`                     | Unique identifier for each review                           |
| `ProductId`              | Unique ID of the product                                     |
| `UserId`                 | ID of the user who left the review                          |
| `ProfileName`            | Username or display name of the reviewer                    |
| `HelpfulnessNumerator`   | Number of users who found the review helpful                |
| `HelpfulnessDenomenator` | Total number of users who evaluated the helpfulness         |
| `Score`                  | Rating given by the user (typically from 1 to 5)            |
| `Time`                   | Unix timestamp for when the review was posted               |
| `Summary`                | Short summary/title of the review                           |
| `Text`                   | Full review content (used for sentiment analysis)           |

---

## 🧠 Usage

This dataset is perfect for tasks such as:
- Sentiment classification (Positive/Negative/Neutral)
- Rating prediction
- Text summarization
- NLP model training

---

## 🔄 Notes

- This dataset is widely available on various platforms.
- For this project, place the file in the `data/` folder and rename it (if needed) to:
  ```
  Reviews.csv
  ```

