---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: compressed Low-light Image Enhancement
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Existing low-light enhancement methods completely ignore the phenomenon of low-light image blocking artifacts caused by compression. After the compressed low-light image is enhanced, it will amplify the blocking artifacts, destroy the texture details, and appear color cast. Therefore, low-light compression image enhancement with a small quality factor is a comprehensive problem involving image enhancement and image restoration. Research on compressed low-light image enhancement has practical significance.


  - title: noisy Low-light Image Enhancement
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * For quality evaluation of compressed images, Chebyshev moments have its advantages. Chebyshev moments of order n are symmetrical. When compressing an image, the image is divided into multiple blocks. Transformation and quantization operations can cause blocking artifacts in the image. The value of the Chebyshev moment is symmetrical. The Chebyshev moment is represented by $P$, and the image block is re-divided (across the boundary of four blocks) by $B$. $P*B$ can detect the horizontal block boundary to capture the characteristics of the blocking artifacts.
        * Chebyshev moments are used to evaluate the image quality of low-light images with different compression factors and different enhancement levels. It is found that this method cannot be correctly evaluated on the compressed low-light images. The reason is that if the pixel value of the entire block is multiplied by the same number, the Chebyshev moment score is the same.
        * Try to improve the Chebyshev moment evaluation method, but we failed. Therefore, it is only used as the quality evaluation of images under normal illumination. Used in the paper.

  - title: Two-dimensional classification of pixels in 3D river image
    company: Multi-dimensional information processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2018-10-01'
    date_end: '2019-06-01'
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying


  - title: Image and video coding
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2019-06-01'
    date_end: '2020-04-30'
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying
        
  - title: Arduino-based automatic soil irrigation system
    company: IoT Lab, James Cook University
    company_url: 'https://www.jcu.edu.au/college-of-science-and-engineering/internet-of-things'
    company_logo: JCU
    location: Australia
    date_start: '2017-07-20'
    date_end: '2017-08-06'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
