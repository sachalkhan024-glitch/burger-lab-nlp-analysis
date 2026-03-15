# burger-lab-nlp-analysis
# 🍔 The Burger Lab: NLP Customer Sentiment Analysis

## 📌 Project Overview
The Burger Lab, a growing restaurant chain, was overwhelmed by unstructured text feedback from customers. The objective of this project was to build a Natural Language Processing (NLP) tool to automatically read, analyze, and categorize customer reviews to determine overall brand sentiment.

## 🛠️ Tools & Methodology
* **Tools:** Python, Pandas
* **Text Standardization:** Utilized Pandas string methods (`.str.lower()`) to clean and normalize raw human input.
* **Logic Engineering:** Developed a custom Python algorithm utilizing the `any()` function to scan text arrays for specific positive and negative keywords.
* **Data Mapping:** Applied the custom function across the dataset using the `.apply()` method for efficient, automated categorization.
* **Aggregation:** Used `.value_counts()` to summarize categorical data into actionable business metrics.

## 📈 Key Business Insights
The automated analysis revealed a critical operational bottleneck:
* **Positive:** 40%
* **Negative:** 40%
* **Neutral:** 20%

**Takeaway:** A 40% negative feedback rate is a severe risk metric for the hospitality sector. The NLP categorization proves that the restaurant is mediocre and requires immediate intervention regarding kitchen QA (undercooked food) and wait times to facilitate future growth.
