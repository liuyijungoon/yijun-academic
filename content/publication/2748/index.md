---
title: "一种利用时序信息的目标跟踪方法"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 王正宁
- 曾浩
- 赵德明
- 彭大伟
- 曾仪
- 刘怡君

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-09-16"
doi: "CN202010974350.3"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: 发明专利
# publication_short: In *ICW*

abstract: 本发明公开了一种利用时序信息的目标跟踪方法，涉及图像处理和计算机视觉领域。该方法使用的方法关键步骤分为如下两个阶段，其中第一阶段输入第一帧与搜索帧，第二阶段输出目标在搜索框上的位置。本发明在特征提取阶段使用非对称卷积模块，选择三种不同形态的卷积核共同使用提升了模型对图像翻转和旋转的鲁棒性，提高网络的抗旋转鲁棒性。在候选框精修中，使用双径候选框分类回归网络，分类支路与回归支路分别处理候选框的分类结果与精修后的候选框，相比单纯依赖卷积网络或全连接网络的网络，进一步提高了结果精度。同时利用时序信息进行目标跟踪后处理，选择更加契合之前结果的跟踪框，减少错误跟踪目标的情况发生。

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

