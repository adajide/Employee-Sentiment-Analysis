# Employee-Sentiment-Analysis
In today’s competitive business landscape, understanding employee sentiment is vital for fostering a productive work environment and improving retention. This study explores the application of Natural Language Processing (NLP) techniques to analyze employee feedback collected from Capgemini’s open-source employee reviews. The primary objective is to extract actionable insights from qualitative data by leveraging both machine learning and deep learning approaches. The dataset underwent rigorous preprocessing, including tokenization, part-of-speech tagging, and vectorization using TF-IDF and Word2Vec. Sentiment analysis was performed using the VADER tool and label encoding, classifying sentiments into positive, negative, and neutral categories. Three supervised machine learning models were the Multinomial Naïve Bayes, Support Vector Machine (SVM), and Random Forest were implemented, with Random Forest achieving the highest accuracy of 95%. Deep learning models, including Recurrent Neural Networks (RNN), Bidirectional LSTM, and Convolutional Neural Networks (CNN), were also employed, with CNN achieving an 86.64% accuracy. The findings highlight that employees expressed more positive sentiments, primarily appreciating work-life balance and job security, while concerns were raised over management and salary. The study concludes that NLP-based sentiment analysis provides a powerful framework for organizations to systematically interpret employee feedback and implement informed, data-driven HR strategies. Future work should consider real-time sentiment tracking and the integration of broader datasets for enhanced accuracy and applicability.** 

# Sentiment Distribution Analysis
Using the sentiment counts:
Positive: 3412 (≈ 63.3%)
Neutral: 1074 (≈ 19.9%)
Negative: 903 (≈ 16.8%)
This distribution indicates a positively skewed sentiment trend in the employee feedback dataset. This can also mean that the dataset is imbalanced.
# Analytical Interpretation
High Positive Sentiment (63.3%)
Suggests that most employees expressed favorable views, particularly in areas like work-life balance, company culture, and job security, as revealed in the word cloud and frequency analysis.
Indicates a strong alignment between employee expectations and organizational policies or support systems.
Moderate Neutral and Negative Sentiment (~37%)
The combined 37% of neutral and negative sentiments is non-trivial, highlighting underlying issues or dissatisfaction in specific areas (e.g., salary concerns, project management inefficiencies, or high pressure).
Suggests the need for targeted sentiment segmentation analysis e.g., breaking down by department, job role, or review rating to locate potential problem clusters.
# Model Implications
Given the class imbalance (positive being dominant), care must be taken in model training to avoid bias toward the majority class.
Precision, recall, and F1-score per class (especially for the negative class) should be used to evaluate model robustness, rather than accuracy alone.
# Business Insight
From an operational standpoint, this high positive sentiment implies a generally healthy workplace culture. However, a data-driven recommendation would be to:
Perform topic modeling on neutral/negative feedback to uncover recurrent themes.
Implement real-time sentiment monitoring pipelines to capture shifts in employee morale as changes occur (e.g., restructuring, policy updates).


