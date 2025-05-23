---
mathjax: true
draft: false
id: 6105
title: Topic Modeling with BERT
date: 2023-11-13
url: /dsblog/topic-modeling-with-bert
tags: [BERT, Topic Modeling, Text Analysis, Natural Language Processing, Machine Learning, Document Clustering, Text Mining]
categories:
  - dsblog
keywords: [BERTopic, Topic Modeling, BERT Applications, Text Analysis, Document Classification, Natural Language Processing, Text Mining, Content Analysis]
header:
    teaser: /assets/images/dspost/dsp6105-Topic-Modeling-with-BERT.jpg
    
excerpt_separator: "<!--more-->"   
author: Hari Thapliyaal   
 
excerpt: Discover how to perform topic modeling using BERT-based approaches. Learn about advanced techniques for identifying and analyzing topics in text collections using transformer-based models and clustering algorithms.   
author_profile: true   
share: true   
toc: true   
toc_sticky: true 
mathjax: "true"
---

![Topic Modeling with BERT](/assets/images/dspost/dsp6105-Topic-Modeling-with-BERT.jpg)

# Topic Modeling with BERT

Key steps in BERTopic modelling are as following.

- Use "Sentence Embedding" models to embed the sentences of the article
- Reduce the dimensionality of embedding using UMAP 
- Cluster these documents (reduced dimensions) using HDBSAN
- Use c-TF-IDF extract keywords, their frequency and IDF for each cluster. 
- MMR: Maximize Candidate Relevance. How many words in a topic can represent the topic?
- Intertopic Distance Map 
- Use similarity matrix (heatmap), dandogram (hierarchical map), to visualize the topics and key_words.
- Traction of topic over time period. Some may be irrelevant and for other traction may be increasing or decreasing.


# Installation
```python
# Installation, with sentence-transformers, can be done using pypi:

pip install bertopic

# If you want to install BERTopic with other embedding models, you can choose one of the following:

# Choose an embedding backend
pip install bertopic[flair, gensim, spacy, use]

# Topic modeling with images
pip install bertopic[vision]
```

# Supported Topic Modelling Techniques 

BERTopic supports all kinds of topic modeling techniques as below.

- Guided	
- Supervised	
- Semi-supervised
- Manual	
- Multi-topic distributions	
- Hierarchical
- Class-based	
- Dynamic	
- Online/Incremental
- Multimodal	
- Multi-aspect	
- Text Generation/LLM
- Merge Models

# Related Resources
- [Advanced Topic Modeling with BERTopic by PINECONE](https://www.pinecone.io/learn/bertopic/)
- [BERTopic by SpaCy](https://spacy.io/universe/project/bertopic)
- [BERTopic github](https://github.com/MaartenGr/BERTopic)
- [BERTopic by Huggingface](https://huggingface.co/blog/bertopic)

# Tools in BERTopic
![Tools-in-BERTopic](/assets/images/dspost/bertopic/Tools-in-BERTopic.png)

# Best Topic Modeling Tool in BERTopic
![BEST-Tools-in-BERTopic](/assets/images/dspost/bertopic/BEST-Tools-in-BERTopic.png)

# BERTopic Model Building
![BERTopic-Model-Building](/assets/images/dspost/bertopic/BERTopic-Model-Building.png)




# Application
- arXiv Dataset (1.7m+ STEP papers)
- Images/photographs
- Historical Documents 
- News articles 
