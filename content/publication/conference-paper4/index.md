---
title: "2nd Place Solution to Instance Segmentation of IJCAI 3D AI Challenge 2020"
authors:
- Kai Jiang
- admin
- Zheng Ju
- Xiang Luo
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2020-10-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). # 这个时间很重要，必须要写，且不可以迟于上面的时间
publishDate: "2020-09-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: In *IJCAI-PRICAI 2020 Workshop*
publication_short: In *IJCAI-PRICAI 2020 Workshop*

abstract: Compared with MS-COCO datasets, the 3D FUTURE has a larger proportion of large objects which area is greater than 96×96 pixels. As getting fine boundaries is vitally important for large object segmentation, Mask R-CNN with PointRend is selected as the base segmentation framework to output high-quality object boundaries. Besides, a better engine that integrates ResNeSt, FPN and DCNv2 and a range of effective tricks that including multi-scale training and test time augmentation are applied to improve segmentation performance. Our best performance is an ensemble of four models(three PointRend-based models and SOLOv2), which won the 2nd place in IJCAI-PRICAI 3D AI Challenge 2020 Instance Segmentation.


# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2010.10957
url_code: ''
url_dataset: https://arxiv.org/abs/2009.09633
url_poster:  "files/ijcai_poster.pdf"
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

