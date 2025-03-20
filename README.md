# Spam-SMS-Detection
This project focuses on building a machine learning model to classify SMS messages as either spam (unwanted or promotional messages) or ham (legitimate, non-spam messages). The goal is to create an effective text classification system that can automatically filter out spam messages, which is a common problem in communication systems.

Dataset

The dataset used in this project is spam.csv, which contains SMS messages labeled as either spam or ham. The dataset is preprocessed to clean and prepare the text data for machine learning.
Dataset Columns:

    Target: Label indicating whether the message is spam or ham.

    Text: The content of the SMS message.

Approach

    Data Preprocessing:

        Remove stopwords, punctuation, and special characters.

        Perform stemming/lemmatization to reduce words to their base forms.

        Convert text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

    Exploratory Data Analysis (EDA):

        Analyze the distribution of spam and ham messages.

        Visualize the data using count plots and word clouds.

    Feature Engineering:

        Extract additional features such as:

            Number of characters.

            Number of words.

            Number of sentences.

    Model Training:

        Train and evaluate multiple machine learning models:

            Multinomial Naive Bayes.

            Random Forest Classifier.

            Support Vector Machine (SVM).

    Model Evaluation:

        Evaluate models using metrics like accuracy, precision, recall, and F1-score.

        Generate confusion matrices and classification reports.

Results

The best-performing model achieved the following results:

    Accuracy: 97.47%

    Precision: 1.00

    Recall: 0.838

    F1-Score: 0.912

Detailed results and visualizations can be found in the Jupyter notebook.
Dependencies

The following Python libraries are required to run this project:

    pandas: For data manipulation and analysis.

    numpy: For numerical computations.

    scikit-learn: For machine learning algorithms and evaluation.

    nltk: For natural language processing tasks.

    matplotlib: For data visualization.

    seaborn: For enhanced data visualization.
