# SMS-Spam-Checker
I started with data cleaning to ensure that the dataset is free from inconsistencies. This involved handling missing values, removing duplicate entries, and formatting text for uniformity. Since SMS messages often contain a mix of uppercase and lowercase letters, abbreviations, and special characters, I standardized them to create a cleaner dataset for analysis.

Next, I performed Exploratory Data Analysis (EDA) to understand the distribution of spam and non-spam messages. I visualized key insights, such as the frequency of words in spam vs. non-spam messages, the average message length, and common patterns in the text. I likely used techniques like word clouds, bar charts, and statistical summaries to identify trends that could help in feature engineering and model selection.

To prepare the text for machine learning, I implemented several text preprocessing techniques, including:

Lowercasing to standardize words.

Tokenization to split messages into individual words.

Removing special characters and punctuation to clean the text.

Removing stopwords like “the,” “is,” and “and,” which do not contribute much to classification.

Stemming to reduce words to their root form (e.g., "running" → "run").

These preprocessing steps helped me transform the raw text into a structured format suitable for machine learning models.


In the final section, I built and trained a machine learning model to classify SMS messages. First, I converted the text into numerical representations using TF-IDF (Term Frequency-Inverse Document Frequency) or CountVectorizer. Then, I trained different classifiers, such as:

Naïve Bayes (a common choice for text classification)

Logistic Regression

Random Forest

Support Vector Machine (SVM)

After training the models, I evaluated their performance using accuracy, precision, recall, and F1-score to determine which model worked best for spam detection.

Through this project, I have successfully implemented a machine learning-based SMS spam detection system. From data cleaning and EDA to preprocessing and model training, I followed a structured workflow to build a reliable classifier. This model can effectively differentiate between spam and legitimate messages, making it useful for real-world applications.
