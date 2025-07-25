<p>
🧠 Project Summary:<br>
This project is a Machine Learning-based language detection system that identifies the language of a given text input. It uses a Multinomial Naive Bayes classifier trained on multilingual textual data to accurately predict the language without any external API like Google Translate.
<br><br>
🎯 Objective:<br>
To build an ML model that can automatically detect the language of a text input based on previously labeled language data.
<br><br>
🧠 Approach:<br>
Load and preprocess the dataset using CountVectorizer to convert text into numerical form.<br>

Split the data into training and testing sets.<br>

Train a Multinomial Naive Bayes model on the vectorized data.<br>

Predict the language of new input text using the trained model.
<br><br>
✅ Advantages:<br>
Fast and lightweight: Uses Naive Bayes, which is efficient for text classification.<br>

Easy to implement: Uses standard Python libraries like scikit-learn and pandas.<br>

Scalable: Can be trained on large multilingual datasets.<br>

Real-time prediction: Quickly identifies language from user input.<br>
</p>