# ⛳️ Evaluation of Golf Course Excellence through NLP Techniques
### A comparative analysis of natural language processing techniques in extracting insights from reviews of top-ranked U.S. golf courses.

> *Note: this project was originally completed as the final submission for Northwestern University's MSDS 453 - Natural Language Processing course taught by Alianna J. Maren, Ph.D.*

## 🗂️ Included in this Repository
- ***NLP_experiment_code.ipynb:*** The Jupyter Notebook containing the initial exploratory data analysis of the novel dataset and the series of NLP experiments completed for the research study (including visualizations)
- ***golf_course_review_corpus.csv:*** The novel dataset created for this NLP research includes 60 golf course reviews from the top 30 ranked golf courses in the United States, according to Golf.com (2 reviews per course).
- ***golf_course_review_scrapper.ipynb:*** The script used to scrape basic information about the top 30 fold courses from Golf.com's website. The scrapped information includes the golf course name, location, course architect, and the year initially constructed.
- ***[Full_Report]_Evaluating_Golf_Course_Excellence_NLP.pdf:*** A pdf of the formal research report written for this research.

## 🔍 Abstract
This study explores the efficacy of various Natural Language Processing (NLP) techniques in extracting meaningful insights from a novel corpus of golf course reviews. By comparing two feature extraction methods—Term Frequency-Inverse Document Frequency (TF-IDF) and Doc2Vec—and two topic modeling techniques—K-Means clustering and Latent Dirichlet Allocation (LDA)—this research aims to determine the best approaches for analyzing textual data related to golf course experiences. The proprietary dataset comprises 60 reviews of the top 30 ranked golf courses in the United States, providing a unique context for evaluating these techniques.

## 🧭 Introduction
Golf courses play a crucial role in shaping the golfing experience, and understanding the attributes that distinguish top-ranked courses can provide valuable insights for designers and stakeholders. Despite the availability of extensive textual data through online reviews, systematic analysis of these reviews to extract meaningful insights has been lacking. This study addresses this gap by employing advanced NLP techniques to analyze golf course reviews, aiming to identify the best NLP techniques for this type of analysis and to identify key features and themes that contribute to the excellence of these courses.

## 🎯 Objectives
1. **Comparative Analysis of NLP Techniques:**
- Feature Extraction: Evaluate the performance of TF-IDF and Doc2Vec in extracting relevant features from golf course review texts.
- Topic Modeling: Analyze the effectiveness of K-Means clustering and LDA in modeling topics within the review corpus.

2. **Extract Insights:**
- Identify common themes and features in the reviews.
- Provide actionable insights for golf course designers and industry stakeholders to enhance course design and player experience.

## 📐 Methods
The research involved preprocessing the text data, applying feature extraction methods, and conducting topic modeling. TF-IDF and Doc2Vec were used for feature extraction, while K-Means clustering and LDA were employed for topic modeling. The performance of these techniques was evaluated using clustering metrics such as Davies-Bouldin Index and Calinski-Harabasz Score, and visualized using dimensionality reduction techniques like PCA and t-SNE.

## 📊 Results
The results demonstrated that Doc2Vec paired with K-Means clustering outperformed TF-IDF in producing well-defined clusters, as indicated by lower Davies-Bouldin scores and higher Calinski-Harabasz scores. The topic modeling results revealed distinct themes related to course design, historical aspects, gameplay, and overall experience.

<p float="left">
  <img src="https://github.com/stefanjenss/NLP_Evaluation_of_Golf_Course_Excellence/assets/118738550/9f69abbd-ae58-4541-b90d-7ee4d972baa4" width="45%" />
  <img src="https://github.com/stefanjenss/NLP_Evaluation_of_Golf_Course_Excellence/assets/118738550/16b75d48-69df-4b4b-8704-daf998ea87cc" width="45%" /> 
</p>

<div color="gray">**Figure.** Visualization of Doc2Vec vector K-Means clusters in 2-dimensional space through multidimensional reduction various techniques. (a) Principal Component Analysis (PCA) multidimensionality reduction. (b) t-distributed Stochastic Neighbor Embedding (t-SNE) multidimensionality reduction.</div>






