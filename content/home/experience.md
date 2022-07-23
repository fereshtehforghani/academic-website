---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience: 
  - title: Research Assistant
    company: Computational Vision and Imaging Lab at York University (CVIL@York)
    company_url: 'https://cvil.eecs.yorku.ca/'
    company_logo: org-m
    location: Toronto, Canada
    date_start: '2022-06-01'
    date_end: ''
    description: 'TBD'  
     
  - title: Remote Summer Intern
    company: Visual Intelligence for Transportation (VITA) Lab, École Polytechnique Fédérale de Lausanne (EPFL)
    company_url: 'https://www.epfl.ch/labs/vita/'
    company_logo: org-x
    location: Lausanne, Switzerland
    date_start: '2021-06-01'
    date_end: '2021-12-31'
    description: This project aim to find natural adversarial examples to test the reliability of human trajectory predictors using density estimation techniques. First, we conducted a litrature review on density estimation techniques, such as [Masked autoregressive flow](https://arxiv.org/abs/1705.07057), [RealNVP](https://arxiv.org/abs/1605.08803) and [Masked autoencoder for distribution estimation](https://arxiv.org/abs/1502.03509). We proceed by using Masked autoregressive flow(MAF) to find natural adversarial examples to test the reliability of human trajectory predictors. Subsequently, we adversarially trained LSTM based predictors and reduced the collision rate up to **35%** in the case of adversarial attack on test data.
    
  - title: Research Assistant
    company: Medical Imaging Lab, Advised by Dr. Mohammad Hossein Rohban (Sharif University of Technology)
    company_url: 'http://sharif.ir/~rohban/'
    company_logo: org-gc
    location: Tehran, Iran
    date_start: '2020-10-01'
    date_end: '2021-06-01'
    description: In medical analysis, supervised and labeled data is used in many cases. However, labeling medical images is extremely difficult, expensive, and time-consuming. In this project, we propose using genralized self-supervised frameworks to extract features from unlabeled images. We pre-trained a U-net encoder with SimCLR, MoCo, and SimSiam. We managed to improved IoU score after fine-tuning with annotated ones **up to 6%**.
    
  - title: Intern
    company: Sinaweb company
    company_url: 'https://sinaweb.net'
    company_logo: sinaweb
    location: Tehran, Iran
    date_start: '2020-07-01'
    date_end: '2021-10-01'
    description: I worked on ML based forgery recognition through handwriting style recognition. The aim of this project was to develop a plagiarism detection method which uses variations in writing style to identify potentially plagiarized passages. We extracted lexical, structural, and syntax features, proposed a regression model to fuse features and predict writing style, and finally, implemented an outlier detection model to find possible plagiarised segments.
  
  - title: Research assistant
    company: Image Processing Lab (IPL), Sharif University of technology
    company_url: 'http://ipl.ce.sharif.edu/'
    company_logo: org-gc
    location: Tehran, Iran
    date_start: '2021-05-01'
    date_end: '2021-09-01'
    description: |2-
        I'm working as a scientific collaborator in the Image Processing Lab (IPL) at Sharif University under the supervision of Prof. Shohreh Kasaei. I am investigating Adversarial attacks against Deep Neural Networks, specifically focusing on 3D pointCloud networks (PointNet and PointNet++).
design:
  columns: '2'
---
