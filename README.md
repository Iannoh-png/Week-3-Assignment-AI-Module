# Week-3-Assignment-AI-Module
# Amazon Product Review Analysis with spaCy (NER & Rule-based Sentiment)

🛒 **Amazon Product Review Analysis**  
This project applies **Natural Language Processing (NLP)** techniques to analyze Amazon product reviews. It uses **spaCy's Named Entity Recognition (NER)** to extract product and brand names and employs a **custom rule-based sentiment analysis** to classify reviews as Positive, Negative, or Neutral.

The project aims to help businesses and analysts uncover actionable insights from customer reviews and improve product strategies.

---

## 📊 Dataset
The project uses two text files:
- `train.ft`
- `test.ft`

Each file contains Amazon product reviews with the following characteristics:
- Varied sentiments (positive, negative, neutral)
- Named entities (products, brands, companies)

**Preprocessing Steps:**
- Reads review text files and removes empty lines.
- Creates dummy datasets if files are missing.
- Loads data for both training and testing.
- Prepares review text for NLP processing.

---

## 🧠 Model Overview
The analysis uses **spaCy's NER model (`en_core_web_sm`)** to extract entities and a **rule-based sentiment classifier** built on keyword matching.

**NLP Workflow:**
- Data Loading & Cleaning
- Named Entity Recognition (spaCy)
- Rule-Based Sentiment Classification
    - Positive & Negative keyword scoring
- Result Summarization per review
- Summary of sentiments and extracted entities for both training and testing datasets

---

## 📈 Evaluation Method
There are no machine learning metrics as this is a rule-based system. Instead:
- Sentiment is determined by comparing counts of positive and negative keywords.
- Extracted entities are reviewed to identify key brands and products.

---

## 🔍 Entity & Sentiment Analysis Example
Sample outputs from the project:
- **Extracted Entities:** `Apple`, `iPhone 15`, `Sony`
- **Sentiment Labels:** Positive, Neutral, Negative

Each review is analyzed for:
- Entity mentions (Products, Brands)
- Sentiment classification

---

## 🛠️ Tools & Technologies
- Python 3.x
- Google Colab
- spaCy
- Pandas

---

## 🎯 Project Objective
This assignment contributes to **automating product review analysis** and aims to:
- Provide quick sentiment summaries from customer reviews
- Extract valuable product and brand mentions using NER
- Support customer feedback analysis and product improvement
