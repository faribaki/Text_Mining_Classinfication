# Text_Mining_Classinfication
The project involves text preprocessing, feature extraction, and classification to categorize news articles based on their titles and body content, utilizing nltk, Scikit-learn, and the SVM algorithm.
The project demonstrates the process of text preprocessing, feature extraction, and classification to categorize news articles based on their title and body descriptions. Key aspects of the project include:
1- Text Preprocessing: Using the nltk library and its Farsi equivalent, hazm, the news articles are cleaned through word tokenization, stemming, and filtering out stop words. A list of stop words is stored in a UTF-8 encoded text file to eliminate irrelevant words from the text.
2- Feature Extraction: We apply TF-IDF (Term Frequency-Inverse Document Frequency) with Scikit-learn’s TfidfVectorizer to create a bag-of-words model. This transforms the news text into numerical features that can be used for classification.
3- Classification: The news articles are classified using the Support Vector Machine (SVM) algorithm, which is trained to predict the correct category based on the features extracted from the title and body of the news articles.
4- Evaluation: The model achieves an overall accuracy of 84%, and the performance is further assessed using a confusion matrix, which shows how well the model categorizes news into their respective labels.
