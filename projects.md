---
layout: page
title: Projects
---

### Twitter Analytics Web Service

<details><summary>High-performance multi-tier web service on the cloud</summary>
<ul>
<li>Worked in a team of 3 to build an application that recommends similar Twitter users </li>
<li>Designed an efficient and fault-tolerant web tier consisting of 3 microservices using Amazon EKS with managed node groups to handle high loads (~tens of thousands of RPS) under a constrained budget</li>
<li>Performed ETL on a large Twitter data set (~1 TB) using Apache Spark on the Azure Databricks platform and deployed storage tier on an AWS RDS MySQL instance</li>
<li>Automated service deployment using eksctl, Terraform and helm charts</li>
<li>Ranked 5th in terms of performance/cost ratio in a live test spanning ~3 hrs</li>
</ul>
</details>


### Machine Learning on the Cloud

<details><summary>Trained and deployed XGBoost on Google AI Platform</summary>
<ul>
<li>Trained and deployed a machine learning model (XGBoost) on the Google AI Platform to predict cab fares in NYC and performed hyperparameter tuning using HyperTune to improve accuracy of model</li>
<li>Processed ride requests in the form of audio and images leveraging a pipeline of cloud ML APIs such as Cloud Text-to-Speech, Cloud Speech-to-Text, Cloud NLP, Directions and AutoML Vision offered by GCP</li> 
<li>Deployed an end-to-end solution on Google App Engine to predict cab fare by combining input pipeline and trained model</li>
</ul>
</details>


### Question Answering

<details><summary><a href="https://youtu.be/Ywuq0DIkklM">Syntactic rule-based QA system</a></summary>
<ul>
<li>Collaborated with a team of 3 to build a rule-based Question Answering system for Wikipedia articles</li>
<li>Developed a hybrid answer generation pipeline consisting of question type identification, top candidate sentences extraction and syntactic rule-based answer formation using dependency parsing and POS tagging</li>
<li>Performed question to declarative sentence conversion, coreference resolution, sentence vector similarity, named-entity recognition and lexical analysis to enhance fluency and conciseness of generated answers</li>
</ul>
</details>

### Question Answering System on SQuAD
- Evaluated simple models using Jaccard Overlap, TF-IDF vectorizer, logistic regressing and distilbert-base-nli-stsb-mean-tokens from the SentenceTransformer library 
- Fine-tuned pre-trained BERT using PyTorch and deployed final model to public endpoint on a Standard_NC6
compute instance on Microsoft Azure

### Rating Prediction for Amazon’s Product Reviews
- Built a multi-class logistic regression model to predict product ratings from 100,000 reviews 
- Data underwent cleaning, exploratory data analysis, feature construction using TfIdf Vectorizer, oversampling  to deal with class imbalance 
- Final model achieved an accuracy of 71% and deployed to public endpoint on Microsoft Azure

### Neural Machine Translation (NMT) from English to Hindi 				  

- Employed supervised __Encoder-Decoder__ architecture facilitated by an enhanced version of Bahdanau’s attention mechanism, Word2Vec and Vecmap
- Final model attained a BLEU score of 35

### Rideshare - A Cloud Based Application

- Developed backend for a cloud-based car-pooling application with REST APIs and MySQL database 
- Implemented load balancing on containerized application deployed on an Amazon AWS EC2 instance

### Sports analytics with Hadoop
- Performed analysis on an Indian Premier League dataset using MapReduce 
- Devised algorithm for ranking players to identify most prolific batsman at each venue based on impact using
PageRank, Spark and Streaming Spark libraries
