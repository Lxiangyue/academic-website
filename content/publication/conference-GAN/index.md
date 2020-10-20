---
title: "SMRGAN: A Sky Map Repair Method Based on GAN for Ultra-long Wavelength Astronomical Observation Array"
authors:
- admin
- Juntao Pu
- Jingwei Yang
- You Song
- Li Deng
date: "2020-10-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date). # 这个时间很重要，必须要写，且不可以迟于上面的时间
publishDate: "2020-09-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Low frequency detection on the back of the moon is a research hotspot in recent years, and the Chang’e project in China has taken a step forward to it. In March 2018, The Chinese Academy of Sciences launched a pilot project of space science, which is ultra long wavelength astronomical observation array background model project (known as “Hongmeng Project” in China). The ultra-long wavelength astronomical observation array consists of one mother satellite and eight daughter satellites, forming a spatially distributed interference array in the lunar orbit. Shielded from the Earth-originated radio frequency interferences, this mission will discovery the unexplored part of electromagnetic spectrum, and will become a milestone in radio astronomy and space exploration. Mapping the sky below 30 MHz using the array of satellites is a major goal of this mission. In order to obtain the whole high-accuracy sky map, conventional method is to continuously increase the satellites’ sampling time, so that the sampling data can approach to the full sampling data step by step. A novel sky map repair method based on generative adversarial networks is proposed by this paper. Generative adversary networks consist of a generator network and a discriminator network, which can achieve image-to-image translation by learning the correspond from image-to-image. Thus, this network can obtain the high-precision sky map from the low-precision sky map. Firstly, using the radio astronomy imaging algorithm to get low-precision sky maps from satellites’ sampling data. Then, the generative adversary networks are trained with the low-precision sky maps and the correspond high-accuracy sky maps as training sets. Finally, another set of low-precision sky maps are used as the test sets to evaluate the network results by comparing the similarity between the outputs of the networks with the high-precision sky maps. The simulation results show that the sky map obtained by this method is more similar to the whole high-precision sky map than conventional method both in the peak signal-to-noise ratio and in the structural similarity, which means that this method can achieve more accurate sky map than conventional method.

# Summary. An optional shortened abstract.
summary: A novel sky map repair method based on generative adversarial networks is proposed by this paper. Generative adversary networks consist of a generator network and a discriminator network, which can achieve image-to-image translation by learning the correspond from image-to-image. Thus, this network can obtain the high-precision sky map from the low-precision sky map. 

tags:
- Source Themes
featured: true

links:
# - name: Custom Link
#  url: http://example.org
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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "Photo by [Academic](https://sourcethemes.com/academic/)"
  focal_point: "Center"
  preview_only: false
  alt_text: An optional description of the image for screen readers.




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

