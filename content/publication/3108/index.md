---
title: "一种基于编解码结构的目标跟踪方法"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 王正宁
- 曾浩
- 潘力立
- 赵德明
- 曾仪
- 刘怡君
- 彭大伟


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-06-09"
doi: "CN202010518310.8"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: 发明专利
# publication_short: In *ICW*

abstract: 本发明公开了一种基于编解码结构的目标跟踪方法，该方法使用编码器‑解码器与鉴别器组合，构建类似生成对抗网络结构，使得编码器提取的特征更加泛化，学习到被跟踪对象的本质特征。由于对象帧中存在被半遮挡、受到光照、运动模糊影响的对象，使得网络受到这些影响更小，更具鲁棒性。使用Focal Loss使用替代传统的交叉熵损失函数，使得网络减少易分类样本的损失，使得模型更关注于困难的、错分的样本，同时平衡正负样本数量的不均衡。使用Distance‑U loss作为回归损失，不仅关注重叠区域，还关注其他的非重合区域，具有尺度不变性，可以为边界框提供移动方向，同时具有较快的收敛速度。

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

