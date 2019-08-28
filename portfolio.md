---
layout: single
title: "Portfolio"
header:
    #overlay_color: "#ffffff"
    #overlay_filter: rgba(255, 255, 255, 0)
    overlay_image: /assets/images/joel-filipe-Wc8k-KryEPM-unsplash.jpg
    caption: "Photo by [Joel Filipe](https://unsplash.com/@joelfilip) on [Unsplash](https://unsplash.com)"
author_profile: true
classes: wide
date: August 27, 2019
feature_row1:
  - image_path: assets/images/deep_learning.png
    portfolio_caption: Photo Credit [Ardon Dertat](https://towardsdatascience.com/applied-deep-learning-part-1-artificial-neural-networks-d7834f67a4f6)
    alt: "placeholder image 2"
    title: "Image Classifier"
    text: "In this project, I have first developed code for an image classifier built with PyTorch in Jupyter Notebook, then converted it into a command line application. Image Classifier predicts 102 flower categories."
    url: "https://github.com/k-bosko/image_classifier"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags: 
        - deep-learning
        - transfer-learning
        - PyTorch

feature_row2:
  - image_path: /assets/images/disaster-response.png
    alt: "placeholder image 2"
    title: "Disaster Response"
    text: "In this project, I built a model for an API that classifies disaster messages. The datasets provided by Figure Eight contain real messages sent during disaster events and their respective categories. The task was to train the supervised ML classifier to automate categorization of the new messages so that different disaster relief agencies would receive only relevant ones."
    url: "https://github.com/k-bosko/disaster_response"
    btn_label: "Code"
    btn_class: "btn--primary"
    url2: "https://github.com/k-bosko/disaster_response"
    btn_label2: "Heroku"
    btn_class: "btn--primary"
    tags: 
    - NLP
    - Flask-app
    - ML Pipeline

feature_row3:
  - image_path: /assets/images/IBM_DS_platform.png
    alt: "placeholder image 2"
    title: "Recommendations with IBM"
    text: "In this project, I implemented different recommendation engines for users of the IBM Watson Studio platform. <br>
    - _Rank Based Recommendations_: recommended the most popular articles based on the highest user interactions <br>
    - _User-User Based Collaborative Filtering_: recommended unseen articles that were viewed by most similar users <br>
    - _Content Based Recommendations_: recommended articles based on similarity of content <br>
    - _Matrix Factorization_: performed SVD to predict articles a user might interact with"
    url: "https://github.com/k-bosko/recommendations_IBM"
    btn_label: "Code"
    btn_class: "btn--primary"
    tags: 
    - recommender system
    - collaborative filtering


---
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}



