# Fake News Detection Project

## Introduction
This project, undertaken at IIIT Bhubaneswar, focuses on developing a robust system to detect fake news. The proliferation of fake news on social media and other platforms has become a significant issue, making it crucial to create automated methods to identify and filter out such content. The project leverages natural language processing (NLP) techniques, machine learning algorithms, and data analysis to achieve this goal.

## Objectives
- To create a dataset of news articles, labeled as fake or real.
- To preprocess the text data for effective analysis.
- To apply machine learning techniques to classify news articles accurately.
- To evaluate the performance of various models and select the best one.

## Steps and Methodologies

### Data Collection
- Collected a comprehensive dataset of news articles from various sources.
- Each article was labeled as either fake or real, providing a solid foundation for supervised learning.

### Data Preprocessing
- **Regular Expressions**: Used for searching and manipulating text. Implemented a regular expression to differentiate between alphabets and other characters, retaining only the characters a-z and A-Z, and replacing any other character with a space.
- **NLTK (Natural Language Toolkit)**: Utilized for text processing and analysis.
  - **Stopwords Removal**: Filtered out common words that do not add significant meaning to sentences, such as "the," "on," "is," etc.
  - **PorterStemmer**: Applied stemming to reduce words to their root form. For example, "learning," "learner," and "prelearning" were reduced to "learn." This involved removing prefixes and suffixes from words.
- **Text Normalization**: Converted all letters to lowercase to ensure uniformity.
- **Tokenization**: Split the text into lists of words for further processing.

### Feature Extraction
- **TfidfVectorizer**: Used to transform the text data into numerical feature vectors. This technique converts a collection of raw documents into a matrix of TF-IDF (Term Frequency-Inverse Document Frequency) features, highlighting the importance of words relative to the document and the entire dataset.

### Model Training
- Trained machine learning models, including:
  - Logistic Regression

### Model Evaluation and Selection
- Compared the models based on their performance metrics.
- Selected the best-performing model for the final fake news detection system.

### Implementation and Deployment
- Implemented the selected model in a user-friendly application.
- Deployed the application to allow users to input news articles and receive real-time predictions on the likelihood of the news being fake.

## Results and Achievements
- Successfully created a fake news detection system with high accuracy.
- Demonstrated the effectiveness of various NLP and machine learning techniques in identifying fake news.
- Provided a valuable tool that can be used by individuals and organizations to combat the spread of misinformation.

## Conclusion
This Fake News Detection project, conducted at IIIT Bhubaneswar, showcases the application of advanced NLP and machine learning methodologies to address a critical issue in today's digital world. The project not only enhances our understanding of text analysis and classification but also contributes to the broader effort of maintaining the integrity of information in the public domain.
