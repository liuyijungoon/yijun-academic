---
title: "一种基于分布式热力图的人脸3D关键点检测方法及系统"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 王正宁
- 何庆东
- 赵德明
- 刘怡君
- 曾仪
- 曾浩
- 张翔

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-08-30"
doi: "CN201910818437.9"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: 发明专利
# publication_short: In *ICW*

abstract: 本发明公开了一种基于分布式热力图的人脸3D关键点检测方法及系统，包括：将数据库中人脸关键点的N个3D参考坐标向量在三个二维平面进行降维投影；采用分布式编码子网络将每个2D参考坐标向量分别编码为一张分布式热力图；通过坐标映射的方式N张分布式热力图合并为一张2D联合热力图；通过concat算法将三张2D联合热力图叠加为3D联合热力图；采用解码子网络将所述3D联合热力图解码为N个3D检测坐标向量。本方法结合了现有的2D及3D人脸关键点检测方法的优点，构建分布式热力图、再通过坐标映射的方式将分布式热力图进行联合，其中的分布式编码子网络模型简单、计算量小，在保持较高检测精度的同时，可进一步减小模型参数量、提高模型运行速度。

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

