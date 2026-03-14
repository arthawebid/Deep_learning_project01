# Hybrid Automated Essay Scoring using Deep Learning and Cosine Similarity

This project implements an **Automated Essay Scoring (AES) system** that evaluates student essays using a hybrid approach combining **Deep Learning (BiLSTM)** and **Cosine Similarity**.

The system analyzes two main aspects of an essay:

1. **Essay Quality**
   Evaluated using a Deep Learning model based on **Bidirectional LSTM**, which captures semantic and contextual relationships in the text.

2. **Answer Relevance**
   Measured using **Cosine Similarity** between the student's essay and a reference answer to determine how closely the response matches the expected topic.

The combination of these methods enables the system to assess both **writing quality and semantic relevance**, providing a more comprehensive automated evaluation.

# Fitur Sistem

Key features of this project include:

* Text preprocessing using NLP techniques
* TF-IDF vectorization for semantic representation
* Cosine Similarity for answer relevance analysis
* Deep Learning model using **BiLSTM**
* Hybrid model combining semantic similarity and essay quality
* Automated prediction of essay scores

# Pipeline Sistem

The system follows the pipeline below:

```
Essay Input
      ↓
Text Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity (Essay vs Reference Answer)
      ↓
Deep Learning Model (BiLSTM)
      ↓
Essay Score Prediction
```

# Teknologi yang Digunakan

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

# Use Case

This project can be used for:

* Educational technology research
* Automated grading systems
* NLP learning projects
* Deep Learning coursework
* Essay evaluation tools

# Contoh Output Sistem

Example output from the system:

```
Similarity Score : 0.78
Similarity Category : Relevant

Predicted Essay Score : 3.65
Essay Quality : Good
```

# Lisensi

This project is intended for **educational and research purposes**.
