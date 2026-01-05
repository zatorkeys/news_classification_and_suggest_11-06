# News Topic Classification & Recommendation System
# Author: Hoang Hung Quan - 23120338 

## Introduction
This project focuses on building a **news topic classification and article recommendation system**
using real-world textual data collected from online news sources.
The system aims to analyze news content, identify distinctive topics,
and recommend relevant articles based on content similarity.

The project is implemented as part of the **Final Project – Introduction to Data Science** course.

---

## Objectives
- Collect and preprocess real-world news data from the Internet
- Explore and analyze textual data using meaningful visualizations
- Extract representative keywords and features from text data
- Build and evaluate models for **topic classification**
- Develop a **content-based article recommendation system**
- Gain insights that support data-driven decision making

---

## Dataset
- **Source**: Online news websites
- **Size**: > 10,000 articles
- **Main attributes**:
  - `Title`: Article title
  - `Description`: Short description / summary
  - `Platform` 
  - `Category`: News category
  - `Area`: Mentioned location or region
---

## 🧪 Data Science Workflow

### 1. Data Collection
- Crawling news articles using Python libraries
- Manual data cleaning and validation
- Storing raw and processed data separately

### 2. Data Preprocessing
- Handling missing and invalid values
- Text normalization (lowercasing, tokenization)
- Removing Vietnamese stopwords
- Combining `Title` and `Description` for text analysis

### 3. Exploratory Data Analysis (EDA)
- Distribution of article lengths
- Category distribution and imbalance analysis
- Top mentioned locations (Area)
- WordCloud visualization for each category
- Keyword frequency analysis using CountVectorizer
- Category-level keyword analysis using TF-IDF

### 4. Feature Extraction
- Bag-of-Words with **CountVectorizer**
- TF-IDF representation with **TfidfVectorizer**
- Unigram and bigram analysis
- Feature comparison and interpretation

### 5. Topic Classification
- Text classification: Transformer, SBERT, PhoBERT

### 6. Article Recommendation System
- Content-based recommendation approach
- Similarity computation using **Cosine Similarity**
- Recommending articles with similar content and topics

---

## Key Insights
- TF-IDF effectively highlights category-specific keywords
- Categories exhibit distinctive vocabularies, supporting classification
- Content-based recommendation performs well for topic-related articles
