---
layout: page
title: Projects
---

### Iterative Back-Translation-Style Data Augmentation for Low Resource ASR and TTS

<details><summary><a href="/assets/pdf/11737 Poster.pdf">Malayalam ASR and TTS</a></summary>
<ul>
<li>Adapted back-translation style data augmentation technique to speech processing by leveraging ASR and TTS outputs to improve each other’s performance iteratively</li>
<li>Implemented a conformer-based ASR model with linear fusion of HuBERT and spectrum-based features. TTS model was a a combination of Glow-TTS and Hifi-GAN</li>
<li>Achieved up to 3.21% and 6.52% reduction in WER and CER respectively for ASR</li>
</ul>
</details>

### Multilingual Speech Recognition

<details><summary>ASR for Malayalam</summary>
<ul>
<li>Contributed to the <a href="https://github.com/espnet/espnet">espnet</a> open source toolkit by implementing Malayalam ASR with only around 6 hours of parallel speech-text data</li>
<li>Achieved WER and CER of 39.2 and 10.4 respectively for a conformer base model</li>
<li>Improved the WER and CER of the base model by 9.2% and 13.4% respectively by implementing a learnable linear fusion of spectrum based and SSL features</li>
<li>Successfully <a href="https://github.com/espnet/espnet/pull/4173">merged</a> ASR recipe into the espnet open-source toolkit</li>
</ul>
</details>

### Multilingual Translation

<details><summary>Low Resource NMT</summary>
<ul>
<li>Explored bilingual and multilingual models for low resource NMT</li>
<li>Increased the BLEU score by up to 3 points by implementing back translation and transfer learning</li>
<li>Studied the effect of vocabulary size, and tokenization algorithms on the performance of NMT</li>
</ul>
</details>

### Multilingual Sequence labeling

<details><summary>Bi-LSTM based POS Tagging</summary>
<ul>
<li>Enhanced the performance of a baseline bi-LSTM model for the task of POS tagging by using multilingual pre-trained BERT embeddings and using a CRF layer</li>
<li>Carried out extensive analysis to understand variation in performance across language families, typology and hyper parameter tuning</li>
</ul>
</details>

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

<details><summary>QA using Machine Learning algorithms</summary>
<ul>
<li>Developed NLP processing pipeline to train and evaluate multiple machine learning models using NLTK library for cleaning and feature extraction of 100000 questions and context paragraphs</li>
<li>Fine-tuned pre-trained BERT model using PyTorch and deployed final model to public endpoint through Microsoft Azure Machine Learning Studio</li>
</ul>
</details>

### Rating Prediction for Amazon’s Product Reviews

<details><summary>Logistic regression to predict product ratings</summary>
<ul>
<li>Built a multi-class logistic regression model to predict product ratings from 100,000 reviews</li>
<li>Data underwent cleaning, exploratory data analysis, feature construction using TfIdf Vectorizer, oversampling  to deal with class imbalance</li>
<li>Final model achieved an accuracy of 71% and deployed to public endpoint on Microsoft Azure</li>
</ul>
</details>

### Neural Machine Translation (NMT) from English to Hindi

<details><summary>Seq2Seq model for NMT</summary>
<ul>
<li>Employed supervised __Encoder-Decoder__ architecture facilitated by an enhanced version of Bahdanau’s attention mechanism, Word2Vec and Vecmap</li>
<li>Final model attained a BLEU score of 35</li>
</ul>
</details>

### Rideshare - A Cloud Based Application

<details><summary>Uber-like cab search application</summary>
<ul>
<li>Developed backend for a cloud-based car-pooling application with REST APIs and MySQL database</li>
<li>Implemented load balancing on containerized application deployed on an Amazon AWS EC2 instance</li>
</ul>
</details>

### Sports analytics with Hadoop

<details><summary>PageRank on Hadoop</summary>
<ul>
<li>Performed analysis on an Indian Premier League dataset using MapReduce </li>
<li>Devised algorithm for ranking players to identify most prolific batsman at each venue based on impact using
PageRank, Spark and Streaming Spark libraries</li>
</ul>
</details>
