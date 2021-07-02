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
  - title: Research assistant
    company: Image Processing Lab (IPL), Sharif University of technology
    company_url: 'http://ipl.ce.sharif.edu/'
    company_logo: org-gc
    location: Tehran, Iran
    date_start: '2021-05-01'
    date_end: ''
    description: |2-
        I'm doing my B.Sc Project in the Image Processing Lab (IPL) at Sharif University under the supervision of Prof. Shohreh Kasaei. I am investigating Adversarial Attack and Defense against PoinNet, specifically focusing on using Web-Scale Nearest-Neighbor Search defenses.
        
  - title: Remote Summer Intern
    company: Visual Intelligence for Transportation (VITA) Lab, École Polytechnique Fédérale de Lausanne (EPFL)
    company_url: 'https://www.epfl.ch/labs/vita/'
    company_logo: org-x
    location: Lausanne, Switzerland
    date_start: '2021-06-01'
    date_end: ''
    description: I'm a remote intern under the supervision of Prof. Alexandre Alahi. This project is about Realistic adversarial attacks on human trajectory predictors.
    
  - title: Research assistant
    company: Medical Imaging Lab, Sharif University of technology
    company_url: ''
    company_logo: org-gc
    location: Tehran, Iran
    date_start: '2020-10-01'
    date_end: '2021-06-01'
    description: I was a research assistant in the Medical Image Analysis Lab at Sharif University under the supervision of Professor Mohammad Hossein Rohban. I worked on contrastive representation learning methods in cell segmentation task. We implemented different frameworks such as SimCLR and MoCo, to train a U-Net with unlabeled cell images and improve IoU score after fine-tuning with labeled ones.
    
  - title: Intern
    company: Sinaweb company
    company_url: 'https://sinaweb.net'
    company_logo: sinaweb
    location: Tehran, Iran
    date_start: '2020-07-01'
    date_end: '2021-10-01'
    description: I worked on methods for intrinsic plagiarism detection using machine learning.The aim of this project was to develop a plagiarism detection method. This method is using variations in writing style to identify potentially plagiarized passages.
design:
  columns: '2'
---
