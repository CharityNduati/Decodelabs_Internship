DecodeLabs Internship — Data Science & Predictive Analytics Portfolio

Welcome to the central repository for the DecodeLabs Data Science & Analytics Internship. This portfolio demonstrates an end-to-end data analytics and machine learning workflow, covering exploratory data analysis, database design, predictive modeling, and natural language processing.

📌 Executive Summary

This repository contains four structured technical projects focused on transforming raw transactional and text data into useful insights:

Project 1: Exploratory Data Analysis (EDA) & Data Cleaning
Project 2: Database Design, Star Schema & SQL Analytics
Project 3: Customer Segmentation & Machine Learning
Project 4: Natural Language Processing (NLP) & Sentiment Analysis
📁 Repository Structure
Decodelabs_Internship/
├── .gitignore
├── README.md
├── Project1.ipynb
├── Project2.ipynb
├── Project3.ipynb
└── Project4.ipynb

Note: Raw datasets and model files are excluded from Git tracking through .gitignore.

🛠️ Tech Stack & Tools
Language: Python
Data Processing: pandas, numpy
Data Visualization: matplotlib, seaborn
Machine Learning: scikit-learn
NLP: NLTK, TF-IDF
Database & Analytics: SQL
Version Control: Git, GitHub
Development: VS Code, Jupyter Notebook
🚀 Projects Overview
🔹 Project 1: Exploratory Data Analysis & Data Cleaning

Objective:
Explore and prepare the retail transaction dataset for analysis and machine learning.

Key Methodology:

Inspected the structure and quality of the dataset.
Identified missing values and handled them appropriately.
Standardized date fields.
Checked numerical variables for outliers.
Performed univariate, bivariate, and multivariate analysis.
Created visualizations to understand sales, customers, products, discounts, and returns.

Key Deliverables:

Cleaned dataset
Exploratory analysis
Data quality findings
Business insights
🔹 Project 2: Database Design, Star Schema & SQL Analytics

Objective:
Transform the retail dataset into a structured relational database that supports business intelligence and SQL analysis.

Key Methodology:

Designed a relational database structure.
Applied star schema concepts.
Separated transaction data from supporting dimension tables.
Used SQL queries for business analysis.
Applied aggregations and window functions to analyze customer and sales activity.

Key Deliverables:

Database schema
SQL queries
Business intelligence analysis
Analytical insights
🔹 Project 3: Customer Segmentation & Machine Learning

Objective:
Use unsupervised machine learning to identify groups of customers based on their purchasing behavior.

Key Methodology:

Created customer-level features from transaction data.
Standardized numerical features using StandardScaler.
Applied Principal Component Analysis (PCA).
Used the Elbow Method and Silhouette Score to evaluate different cluster sizes.
Applied K-Means clustering.
Interpreted the resulting clusters as customer personas.

Key Deliverables:

Customer segmentation model
PCA analysis
Cluster evaluation
Customer personas
Business recommendations
🔹 Project 4: Natural Language Processing (NLP) & Sentiment Analysis

Objective:
Demonstrate an end-to-end NLP pipeline for processing text and classifying sentiment.

Key Methodology:

Cleaned and normalized text data.
Used custom stop-word filtering while retaining important negation words such as not, no, and never.
Applied POS-guided lemmatization using WordNetLemmatizer.
Converted text into numerical features using TF-IDF.
Used unigram and bigram features with ngram_range=(1, 2).
Trained and compared:
Multinomial Naive Bayes
Complement Naive Bayes
Linear SVM
Evaluated the models using accuracy, precision, recall, and F1-score.

Key Deliverables:

Text preprocessing pipeline
TF-IDF feature matrix
Sentiment classification models
Model comparison
Sentiment analysis results

Note: The original retail dataset did not contain customer review text. Synthetic review text was therefore created from the available transaction information to demonstrate the NLP pipeline. The results should be interpreted as a demonstration of the workflow rather than as a measure of real customer sentiment.

🚦 How to Run Locally
1. Clone the Repository
git clone https://github.com/CharityNduati/Decodelabs_Internship.git
cd Decodelabs_Internship
2. Create a Virtual Environment
python -m venv venv

Activate the environment on Windows:

venv\Scripts\activate
3. Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn nltk jupyter
4. Download Required NLTK Resources

For Project 4, run:

import nltk

nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger_eng')
5. Launch Jupyter Notebook
jupyter notebook

Open the project notebooks and run the cells in order.

👤 Author

Charity Nduati

GitHub: https://github.com/CharityNduati
Portfolio: DecodeLabs Data Science & Analytics Internship
📄 License

This repository is licensed under the MIT License and is intended for learning and educational purposes.