---
title: "一种全局多阶段目标跟踪方法"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 王正宁
- 赵德明
- 曾浩
- 曾仪
- 奚伟航
- 刘怡君


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-09-16"
doi: "CN202010972556.2"

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

abstract: 本发明公开了一种全局多阶段目标跟踪方法，涉及图像处理和计算机视觉领域。该方法使用的方法关键步骤分为如下两个阶段，第一阶段输入为第一帧与搜索帧，第二阶段输出一系列带有置信度的跟踪目标边界框。本发明在目标跟踪网络的特征提取阶段使用可变形卷积结构，使得网络对目标的特征提取具有更强的形变鲁棒性。在区域候选网络使用导向锚框机制，让网络自行学习产生锚框，使得锚框与当前输入特征有更好的契合程度，同时在使用不同数据集进行训练时，模型对不同的数据集也有良好的拟合能力。使用正样本判别阈值递增的多阶段级联的候选框分类回归网络进行候选框的精修，使得候选框质量与不同阶段的判别阈值相匹配，进一步提升结果框的精确度。

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

