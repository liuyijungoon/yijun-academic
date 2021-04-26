---
title: "PD-GAN: Perceptual-Details GAN for extremely noisy low light image enhancement"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yijun Liu
- Zhengning Wang
- Yi Zeng
- Hao Zeng
- Deming Zhao


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-04-20"
# doi: "CN202011036966.2"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)
publication_short: In *ICASSP*

abstract: Extremely noisy low light enhancement suffers from highlevel noise, loss of texture detail, and color degradation. When recovering color or illumination for images taken in a dark environment, the challenge for networks is how to balance the enhancement for noise and texture details for a good visual effect. A single network is not suitable for solving the ill-posed problem of mapping the input image’s noise to the clear target in the ground truth. To solve the problems, we pro-pose perceptual-details GAN (PD-GAN) utilizing Zero- DCE to initially recover illumination and combine residual dense-block Encoder-Decoder structure to suppress noise while finely adjusting the illumination. Besides, fractional differential gradient masks are integrated into the discriminator to enhance details. Experiment results demonstrate that PD-GAN outperforms other methods on the extremely low-light image dataset.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

