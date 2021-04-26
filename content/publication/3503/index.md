---
title: "一种面向航拍影像的目标跟踪方法"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 王正宁
- 赵德明
- 何庆东
- 蓝先迪
- 曾浩
- 曾怡
- 刘怡君

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-10-30"
doi: "CN201911043274.8"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: 发明专利
# publication_short: In *ICW*

abstract: 本发明公开了一种面向航拍影像的目标跟踪方法，包括：S100在上一帧的目标位置周围，执行增量式的搜索策略；S200采样的样本经过孪生网络和区域推荐网络，得到预测位置的目标；S300通过计算预测位置的目标与目标模板的相似度判断预测是否成功；若预测成功，则保存具体的目标位置并用于下一次预测；预测失败时，若系统在连续的N帧内有n帧预测失败，则判断为目标丢失，进入步骤S400，否则判断为误检测；S400将检测框初始化，并置于当前帧图像的中心点，执行增量式的搜索策略，重新检测和跟踪，直到重新定位到目标。本发明对于目标被遮挡后的重新检测速度有明显的提升，减少了检测框的误采样计算，能够快速的重新定位。

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

