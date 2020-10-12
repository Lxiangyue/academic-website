---
title: "2nd Place Solution to Instance Segmentation of IJCAI 3D AI Challenge 2020"
authors:
- admin
- Zheng Ju
date: "2020-09-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: In this report, we introduce the 2nd place solution to the Instance Segmentation track in IJCAI-PRICAI 3D AI Challenge 2020. As getting fine object boundaries is vitally important for the large objects that count a higher proportion in this dataset, Cascade R-CNN with PointRend is selected as the base segmentation framework to output the high-quality object boundaries. Besides, a range of tricks, including focal loss, deformable convolution networks v2, are applied to improve segmentation performance. Our final submission is an ensemble of four models(three models are Mask R-CNN variants, and the other is SOLOv2), which achieve the 2nd place both in the first challenge season and the final season.

# Summary. An optional shortened abstract.
summary: As getting fine object boundaries is vitally important for the large objects that count a higher proportion in this dataset, Cascade R-CNN with PointRend is selected as the base segmentation framework to output the high-quality object boundaries. Besides, a range of tricks, including focal loss, deformable convolution networks v2, are applied to improve segmentation performance. Our final submission is an ensemble of four models(three models are Mask R-CNN variants, and the other is SOLOv2), which achieve the 2nd place both in the first challenge season and the final season.


tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

