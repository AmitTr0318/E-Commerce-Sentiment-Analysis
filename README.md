# E-Commerce-Sentiment-Analysis

### Project Title: **Sentiment Analysis and Visualization of E-Commerce Reviews**

---

### **Objective**
The project aims to analyze customer reviews from various e-commerce platforms to extract meaningful insights, including sentiment classification (positive, neutral, and negative). The goal is to identify trends in customer satisfaction and platform performance, leveraging Python for data analysis, visualization, and machine learning.

---

### **Dataset**
- **Source**: Customer review dataset for multiple e-commerce platforms (Blinkit, Zepto, JioMart, etc.).
- **Columns**:
  - **Rating**: Numeric rating given by the customer.
  - **Date**: Date of the review.
  - **Review**: Textual feedback provided by the customer.
  - **Platform**: Platform on which the review was posted.

---

### **Key Steps**
1. **Data Preprocessing**:
   - Converted the `date` column to a proper datetime format.
   - Removed duplicates and handled missing values.
   - Extracted month-year for time-based analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of ratings.
   - Studied platform-specific trends in ratings and reviews.

3. **Sentiment Analysis**:
   - Used **TextBlob** to classify review text into positive, neutral, and negative sentiments.
   - Added a `sentiment` column to the dataset to store results.

4. **Visualization**:
   - Created visualizations to understand platform performance:
     - Overall sentiment distribution.
     - Platform-wise sentiment counts (bar chart).
     - Monthly trends in reviews and ratings.

5. **Machine Learning**:
   - Built a machine learning model to classify sentiments using:
     - **TF-IDF Vectorization** for text preprocessing.
     - **Gradient Boosting Classifier** for sentiment prediction.
   - Evaluated model accuracy and performance using classification metrics.

---

### **Technologies and Libraries**
- **Python**: For data manipulation, text analysis, and machine learning.
- **Pandas**: Data preprocessing and analysis.
- **TextBlob**: Sentiment classification.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning model development.

---

### **Outcomes**
- Identified sentiment trends for each platform, helping highlight customer satisfaction levels.
- Visualized insights through detailed charts:
  - Sentiment distribution by platform.
  - Time-based trends in reviews.
- Achieved a high accuracy in sentiment classification using machine learning.

---

### **Skills Demonstrated**
- Data Cleaning and Preprocessing
- Sentiment Analysis using NLP
- Data Visualization
- Feature Engineering (TF-IDF)
- Machine Learning Model Development and Evaluation

---

### **Use Case**
This project can be used by e-commerce platforms to:
- Understand customer sentiment trends.
- Improve services based on customer feedback.
- Identify problem areas to enhance customer satisfaction.
