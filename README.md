# Fake / Real Review Detection

## Project Description
This is a simple **Data Science project** to detect whether a review is **fake** or **real** using **Python**.  
The project uses **Naive Bayes classifier** and **CountVectorizer** to analyze the review text and predict its authenticity.

---

## Dataset
The dataset contains **text reviews** and their **labels**:

- `review_text` → Review text  
- `label` → 0 = Real, 1 = Fake  

A small sample dataset (`reviews.csv`) is included for testing.

---

## How It Works
1. Load the dataset using **pandas**.
2. Convert the review text into numbers using **CountVectorizer**.
3. Train a **Naive Bayes** model.
4. Test the model on new reviews.

---

## Requirements
- Python 3.x  
- Libraries: `pandas`, `scikit-learn`

Install dependencies using:

```bash
pip install pandas scikit-learn
