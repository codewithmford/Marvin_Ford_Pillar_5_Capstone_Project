# Capstone: Netflix Content-Based Recommender System

## Project Description
This capstone project develops a content-based recommender system designed to help users discover relevant Netflix titles when user interaction data (such as ratings or watch history) is unavailable. Large streaming catalogs often overwhelm users, making content discovery inefficient. This project addresses that challenge by relying entirely on title metadata and content similarity, rather than behavioral data.

The system is designed to operate effectively under cold-start conditions, where traditional collaborative filtering methods struggle. Instead of predicting user preferences, the model retrieves semantically similar content using descriptive metadata such as genres, descriptions, cast, and country.

---

## Problem Statement
Traditional recommender systems depend heavily on user behavior, which introduces challenges such as:
- Cold-start problems for new users or new content  
- Popularity bias toward frequently viewed titles  
- Limited discovery of long-tail content  

This project addresses the following question:

**How can relevant, diverse, and explainable Netflix content be recommended using only title-level metadata?**

The objective is not to predict individual user behavior, but to improve content discovery, reduce excessive browsing, and promote fair catalog exposure using transparent and auditable methods.

---

## Dataset Source and Description
- **Dataset Name:** Netflix Movies and TV Shows  
- **Source:** Kaggle  
  https://www.kaggle.com/datasets/shivamb/netflix-shows  
- **Total Records:** 8,809 titles  
- **Unit of Analysis:** Individual movie or TV show  
- **Key Features:**  
  - title  
  - description  
  - listed_in (genres)  
  - cast  
  - director  
  - country  
  - type  
  - release_year  

### Dataset Setup
Download the dataset from Kaggle and place it in the following directory: data/raw/netflix_titles.csv


---

## Installation

1. Clone or download this repository  
2. Install dependencies using: pip install -r requirements.txt
3. Ensure the dataset is located at: data/raw/netflix_titles.csv


---

## How to Run the Code

1. Open the project directory.
2. Run the main notebook **in full**: Marvin_Ford_Pillar_5_Capstone_Project.ipynb
3. This notebook contains the complete pipeline, including:
   - Data loading and preprocessing  
   - Feature engineering  
   - Similarity modeling  
   - Evaluation and analysis  
   - Final recommendation generation  

4. The additional notebooks in the repository contain modular or intermediate steps and may be referenced if needed, but the main notebook runs end-to-end on its own.

---

## Results Summary
- **High relevance:** Consistent Precision@K across multiple anchor titles  
- **Improved diversity:** Controlled reduction of repetitive recommendations  
- **Stable behavior:** Low variance across different content categories  
- **Explainability:** Recommendations are interpretable through content similarity  
- **Bias awareness:** Exposure risks monitored and mitigated using diversity metrics  

The system balances relevance, diversity, and fairness rather than optimizing a single metric.

---

## Model Artifacts

After running the full pipeline, the trained artifacts are automatically saved to: models/
The file: final_recommender_artifacts.pkl 
is generated during execution and is intentionally excluded from version control due to file size.

---

## Author Information

**Marvin L. Ford, MBAA**  
Pillar 5 Capstone Project – Netflix Content-Based Recommender System  
Post Graduate Diploma in AI & ML by AIM - Asian Institute of Management





