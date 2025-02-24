# 📢 Amazon Alexa Reviews Sentiment Analysis  

This project performs **Natural Language Processing (NLP)** on Amazon Alexa reviews to classify sentiments using **Decision Tree** and **Random Forest** models. It includes data preprocessing, visualization, and model training with **Flask integration** for deployment.  

## 🚀 Features  
✔️ Sentiment analysis of Amazon Alexa reviews  
✔️ Data visualization using Matplotlib & Seaborn  
✔️ Word cloud representation of positive & negative words  
✔️ Preprocessing with stop words removal & stemming  
✔️ Model training using **Decision Tree** & **Random Forest**  
✔️ Hyperparameter tuning with **GridSearchCV**  
✔️ Flask-based web interface for predictions  

## 📂 Dataset  
The dataset contains Amazon Alexa reviews with:  
- **verified_reviews** (Text of the review)  
- **rating** (Star rating of the review)  
- **feedback** (1 for positive, 0 for negative)  
- **variation** (Alexa device variant)  

## 📊 Exploratory Data Analysis  
- Distribution of ratings & feedback  
- Variation-wise rating analysis  
- Word clouds for positive & negative words  

## 🛠️ Tech Stack  
- **Python**  
- **Flask**  
- **NLTK** (Text preprocessing)  
- **Scikit-learn** (Machine Learning)  
- **Matplotlib & Seaborn** (Data Visualization)  
- **Pandas & NumPy** (Data Manipulation)  
- **Pickle** (Model saving)  

## 🔧 Model Training  
1. **Preprocessing**: Tokenization, Stopword removal, Stemming  
2. **Feature Extraction**: CountVectorizer (Bag of Words)  
3. **Training**:  
   - **Decision Tree Classifier**  
   - **Random Forest Classifier**  
4. **Hyperparameter Tuning**: GridSearchCV  

