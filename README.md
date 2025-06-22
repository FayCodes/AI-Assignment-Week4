# AI-Assignment-Week4

# 🎯 Predicting Priority Levels from Clinical Data

This notebook uses predictive modeling to classify medical cases into *High*, *Medium*, or *Low* priority levels based on patient features. It’s part of a practical exercise in ethical AI and healthcare resource allocation.

## 📄 About the Notebook

All the work is contained in a single Jupyter Notebook:

- Data cleaning and encoding
- Target label creation (`priority`)
- Handling class imbalance using class weights
- Training a Random Forest Classifier
- Model evaluation with accuracy, F1 score, and a confusion matrix
- Ethical reflection on fairness and representation

## 🧠 Purpose

This project explores how predictive analytics can be used to **support timely decision-making** in medical or organizational contexts. It also reflects on how models can unintentionally carry bias—and what we can do about it.

## 🧪 Technologies Used

- Python 3.x  
- pandas, numpy  
- scikit-learn  
- seaborn, matplotlib  

Install dependencies with:

```bash
pip install -r requirements.txt

🧭 Ethical Reflection
The project includes a reflection on potential biases in the dataset and how fairness tools like IBM AI Fairness 360 can help detect and address them.
