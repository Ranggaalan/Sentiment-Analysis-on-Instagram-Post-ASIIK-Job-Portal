# 📌 Instagram Sentiment Analysis: ASIIK Job Portal

## 📖 Project Description
This project analyzes public sentiment towards an Instagram post from **Dinas Perindustrian dan Tenaga Kerja** about the **ASIIK job portal**. The objective is to classify user comments into **positive, negative, and neutral** sentiments, providing insights into public perception and engagement.
![image](https://github.com/user-attachments/assets/9094035e-c2ee-480d-b136-d2476c0857aa)


## 📝 Dataset
- **Source:** Instagram comments from the ASIIK job portal post.
- **Features:**
  - **Text:** User comments.
  - **Sentiment Labels:** Positive, Negative, Neutral.

## 🔍 Methodology
### 📌 Data Collection
- Scraping Instagram comments from the post.

### 📌 Text Preprocessing
- **Text Cleaning:** Removing special characters, URLs, and unnecessary whitespace.
- **Tokenization:** Splitting text into individual words.
- **Stopword Removal:** Filtering out common words that do not contribute to sentiment.
- **Stemming & Lemmatization:** Reducing words to their root forms.
- **Feature Extraction:** Converting text into numerical vectors using **TF-IDF**.

### 📌 Sentiment Classification
Several machine learning models were trained and evaluated:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- **Random Forest**
- **Decision Tree**
- **Gradient Boosting**
- **K-Nearest Neighbors (KNN)**

### 📌 Model Evaluation
- **Metrics Used:** Accuracy, Precision, Recall, F1-score.
- **Best Performing Models:** SVM and Decision Tree achieved the highest accuracy.

## 📊 Results

### Sentimen Positif
![image](https://github.com/user-attachments/assets/c629d59d-3580-4f4b-881b-e997dc0abb11)

### Sentimen Negatif
![image](https://github.com/user-attachments/assets/86152d86-2b1a-4fa5-ac42-1730491268f3)

### Sentimen Netral
![image](https://github.com/user-attachments/assets/95fef3c5-076b-4039-84ab-030eb738240c)

### Sentimen Results
![Uploading image.png…]()


### 📌 Sentiment Distribution
| Sentiment | Percentage |
|-----------|------------|
| Negative  | 51%        |
| Neutral   | 8%         |
| Positive  | 32%        |

### 📌 Best Performing Models
| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 47%      |
| Support Vector Machine (SVM) | 35% |
| Naive Bayes          | 41%      |
| Random Forest        | 35%      |
| Decision Tree        | 41%      |
| K-Nearest Neighbors (KNN) | 47% |
| Gradient Boosting    | 47%      |

### 📌 Visualization
- Sentiment distribution charts.
- Accuracy comparison between models.
- Word clouds representing frequent words in each sentiment category.

## 💻 Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, NLTK, Seaborn, Matplotlib.
- **Machine Learning**: Text classification models.
- **Data Visualization**: Matplotlib, Seaborn, and WordCloud.

## 🔥 Conclusion
This analysis provides insights into **public perception of the ASIIK job portal** based on Instagram comments. The findings help authorities understand user feedback and improve engagement strategies.
