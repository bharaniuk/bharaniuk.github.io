---
layout: page
title: Projects
---

### Iterative Back-Translation-Style Data Augmentation for Low Resource ASR and TTS \[[Project Poster](/assets/pdf/11737 Poster.pdf)\]

<details><summary>Novel iterative back-translation style approach to augment data for Automatic Speech Recognition (ASR) and Text to Speech (TTS)
for Malayalam, a truly low resource language</summary>
<ul>
<li>Adapted back-translation style data augmentation technique to speech processing by leveraging ASR and TTS outputs to improve each other’s performance iteratively</li>
<li>Output of ASR used to create a pseudo-parallel corpus as input to fine-tune TTS and vice versa</li>
<li>Implemented a conformer-based ASR model with linear fusion of HuBERT and spectrum-based features. TTS model was a combination of Glow-TTS and Hifi-GAN</li>
<li>Achieved up to <b>6.91%</b> and <b>10.87%</b> reduction in Word Error Rate (WER) and Character Error Rate (CER) respectively for ASR and a 2.91% improvement in Mel-cepstral distortion (MCD) for TTS</li>
</ul>
</details>

### Multilingual Speech Recognition \[[Code](https://github.com/espnet/espnet/tree/master/egs2/ml_openslr63/asr1)\]

<details><summary>Automatic Speech Recognition for Malayalam on <b>espnet</b></summary>
<ul>
<li>Contributed to the <a href="https://github.com/espnet/espnet">espnet</a> open source toolkit by implementing Malayalam ASR with only around 6 hours of parallel speech-text data</li>
<li>Achieved WER and CER of <b>39.2</b> and <b>10.4</b> respectively for a conformer base model</li>
<li>Improved the WER and CER of the base model by <b>9.2%</b> and <b>13.4% </b> respectively by implementing a learnable linear fusion of spectrum based and HuBERT self-supervised learning features</li>
<li>Successfully <a href="https://github.com/espnet/espnet/pull/4173">merged</a> ASR recipe into the espnet open-source toolkit</li>
</ul>
</details>

### Multilingual Translation

<details><summary>NMT for low resource languages Azerbaijani and Belarus, to and from English</summary>
<ul>
<li>Improved baseline bilingual and multilingual models for low resource NMT with fairseq as the MT framework on top of PyTorch</li>
<li>Implemented multiple methods such as data augmentation via back translation and cross-lingual transfer learning to improve multilingual transfer</li>
<li>Achieved a <b>3</b> point increase in BLEU score</li>
<li>Studied the effect of vocabulary size, and tokenization algorithms on the performance of NMT</li>
</ul>
</details>

### Multilingual Sequence labeling
<details><summary>Bi-LSTM based POS Tagging with mBERT and Conditional Random Fields</summary>
<ul>
<li>Enhanced the performance of a baseline bi-LSTM model written in PyTorch for the task of POS tagging by utilizing pre-trained multilingual BERT embeddings</li>
<li>Gained <b>20.6%</b> and <b>3%</b> in accuracy for Tamil and English respectively</li>
<li>Performed extensive analysis to understand variation in performance across language families, typology and hyper-parameter</li>
</ul>
</details>

### COVID-19 Data Dashboard \[[Code](https://github.com/bharaniuk/final-project-dunder-mifflin-paper-company)\]

<details><summary>Streamlit web-app powered by Altair and Python</summary>
<ul>
<li>An interactive web application that analyzes how different states in the US approached the COVID-19 pandemic</li>
<li>Through visualization techniques it was seen that as soon as the ICU bed utilization crosses the ~75% barrier, the number of deaths see a sharp incline</li>
<li>The dashboard empowers the viewer with insights and answers to questions related to the impact of COVID-19 on existing medical infrastructure and whether a strict government policy response entails lower morbidity</li>
</ul>
</details>


### Twitter Analytics Web Service

<details><summary>Fully managed high-performance multi-tier web service with Amazon EKS and RDS. 
Performed ETL using Spark to reduce 1TB Twitter data to 60GB</summary>
<ul>
<li>Worked in a team of 3 to build a Vertx-based web application that recommends similar Twitter users </li>
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


### Question Answering \[[Project Video](https://youtu.be/Ywuq0DIkklM)\]

<details><summary>Syntactic rule-based QA system</summary>
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
