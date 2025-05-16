# 📚 Text and Hypertext Categorization using SVM

This project demonstrates how to use **Support Vector Machines (SVM)** to automatically classify text documents—such as news articles, emails, or web pages—into specific categories. The model is trained using **TF-IDF vectorization** for feature extraction and an SVM classifier for accurate categorization. Built and tested using **Google Colab** and **Scikit-learn**.

---

## 🧠 Project Description

Text and hypertext categorization is the process of assigning predefined labels to unstructured text. In this project, we:

- Preprocess raw text using **TF-IDF vectorization**
- Train an **SVM classifier**
- Use the trained model to classify new text
- Visualize prediction confidence using bar charts
- Experiment with a **threshold-based approach** to classify documents as general or category-specific

---

## 🗂️ Dataset

We used the **20 Newsgroups** dataset from Scikit-learn, focusing on the following categories:

- `rec.sport.hockey`
- `sci.med`

You can easily extend or modify the categories to suit other domains like spam detection, sentiment analysis, or topic tagging.

---

## 📥 Sample Input

```text
"The new AI model has outperformed previous benchmarks in natural language understanding."
```

## 📤 Sample Output
```text
Predicted Category: sci.med
Confidence Scores: [0.28, 0.72]
```
