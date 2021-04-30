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
        
        * Existing low-light enhancement methods completely ignore the phenomenon of low-light image blocking artifacts caused by compression. After the compressed low-light image is enhanced, it will amplify the blocking artifacts, destroy the texture details, and appear color cast. Therefore, low-light compression image enhancement with a small quality factor is a comprehensive problem involving image enhancement and image restoration. Research on compressed low-light image enhancement has practical significance.


  - title: Chebyshev moments to evaluate blockiness
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        
        * For quality evaluation of compressed images, Chebyshev moments have its advantages. Chebyshev moments of order n are symmetrical. When compressing an image, the image is divided into multiple blocks. Transformation and quantization operations can cause blocking artifacts in the image. The value of the Chebyshev moment is symmetrical. The Chebyshev moment is represented by $P$, and the image block is re-divided (across the boundary of four blocks) by $B$. $P*B$ can detect the horizontal block boundary to capture the characteristics of the blocking artifacts.
        * Chebyshev moments are used to evaluate the image quality of low-light images with different compression factors and different enhancement levels. It is found that this method cannot be correctly evaluated on the compressed low-light images. The reason is that if the pixel value of the entire block is multiplied by the same number, the Chebyshev moment score is the same.
        * Try to improve the Chebyshev moment evaluation method, but we failed. Therefore, it is only used as the quality evaluation of images under normal illumination. Used in a paper "Compressed low-light image enhancement and restoration with content migration transformer".
        
  - title: noisy Low-light Image Enhancement
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        
        * There are two kinds of datasets in the field of low-light image enhancement, including RAW format and sRGB format images. Since RAW format images are converted to sRGB format, it will loss a lot of information and amplify noise. So extreme low-light images are often in RAW format and low-light images are sRGB images. In life, there are a large number of extreme low-light images in sRGB format, and it is of practical significance to study the enhancement of sRGB extreme low-light images.
        * Convert the RAW format dataset SID proposed in the Learning to See In the Dark paper to sRGB dataset. We combine residual denseblock, Unet and Zero-DCE for low light enhancement under the framework of GAN. Use perceptual loss, L1 loss, and fractional differential loss to counter loss to guide the network to complete low-light image enhancement.
        *Successfully complete low-light image enhancement, restore illuminance and color, eliminate noise, and enhance texture details. Based on this, complete the paper "PD-GAN: Perceptual-Details GAN for extremely noisy low light image enhancement".

  - title: Fractional differential
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        
        * Compared with integer order differentiation, fractional order differentiation has a better ability to extract the details of smooth regions. This feature allows it to help the algorithm preserve and enhance the details in low-light images and suppress noise.
        * Preprocess the low-light image or design it as a loss function.
        * Successfully improve the performance of low-light image algorithms, enhance details, and eliminate noise. Based on this, complete the paper "Structure-Preserving Extremely Low Light Image Enhancement with Fractional Order Differential Mask Guidance".


  
  - title: Two-dimensional classification of pixels in 3D river image
    company: Multi-dimensional information processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2018-10-01'
    date_end: '2019-06-01'
    description: |2-


  - title: Image and video coding
    company: Image Processing Institute, UESTC
    company_url: ''
    company_logo: uestc
    location: China
    date_start: '2019-06-01'
    date_end: '2020-04-30'
    description: |2-

        
  - title: Arduino-based automatic soil irrigation system
    company: IoT Lab, James Cook University
    company_url: 'https://www.jcu.edu.au/college-of-science-and-engineering/internet-of-things'
    company_logo: JCU
    location: Australia
    date_start: '2017-07-20'
    date_end: '2017-08-06'
    description: 

design:
  columns: '2'
---
