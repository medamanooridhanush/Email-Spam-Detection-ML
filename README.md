 📧 Email Spam Detection

This project demonstrates how to detect spam emails using Natural Language Processing (NLP) and various Machine Learning classifiers. It includes data cleaning, visualization, model training, and performance evaluation.
---

 📂 **Project Structure**

* **Notebook:** `email_Spam_Detection.ipynb`
* **Dataset:** `spam.csv` (included in this project and originally taken from GitHub)

---

### ⚙️ **Libraries Used**

* **pandas:** For data handling
* **numpy:** For numerical operations
* **nltk:** For text preprocessing (stopwords)
* **wordcloud & matplotlib:** For visualization
* **scikit-learn:** For feature extraction (TF-IDF) and classification models

---
 🧾 **Workflow**

1. **Install Dependencies:** Install required packages like `nltk` and `wordcloud`.
2. **Load Dataset:** Load `spam.csv` using pandas.
   📌 **Note:** The dataset is taken from a public GitHub repository and is included with this project.
3. **EDA:** Check dataset shape, info, and null values.
4. **Text Preprocessing:**

   * Convert to lowercase
   * Remove email addresses & punctuation
   * Remove stopwords
   * Add message length columns
5. **Visualization:** Generate word clouds for spam vs. ham messages.
6. **Feature Extraction:** Use TF-IDF vectorizer to convert text to numeric form.
7. **Model Building:** Train and test the following classifiers:

   * Naive Bayes
   * Support Vector Machine (SVM)
   * Decision Tree
   * Random Forest
   * Logistic Regression
8. **Evaluation:** Compare model performance using accuracy, classification report, and confusion matrix.
9. **Result:** SVM classifier performs the best for this dataset.
10. **Output:** Filtered spam messages and prediction results.

---

   
**✅ Result**

This project shows that the **SVM classifier** provides the highest accuracy for spam email detection in this dataset.


📌 **Notes**
The `spam.csv` dataset is included and was originally obtained from a GitHub public repository.
This is a basic implementation; you can improve it with advanced NLP techniques or deep learning models.

**Happy Learning & Spam Filtering! ✉️🔍✨**
