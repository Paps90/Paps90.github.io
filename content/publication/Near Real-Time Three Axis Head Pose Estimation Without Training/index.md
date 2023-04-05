---
title: "Near Real-Time Three Axis Head Pose Estimation Without Training"
authors:
- Andrea F. Abate
- admin
- Carmen Bisogni
- Michele Nappi
- Stefano Ricciardi 
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2019-05-17T00:00:00Z"
doi: "10.1109/ACCESS.2019.2917451"

publishDate: "2018-12-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access, vol. 7, pp. 64256-64265, 2019."
publication_short: ""

abstract: Head pose estimation methods evaluate the amount of head rotation according to two or three axes, aiming at optimizing the face acquisition process, or extracting neutral-pose frames from a video sequence. Most approaches to pose estimation exploits machine-learning techniques requiring a training phase on a large number of positive and negative examples. In this paper, a novel pose estimation method that exploits a quad-tree-based representation of facial features is described. The locations of a set of landmarks detected over the face image guide its subdivision into smaller and smaller quadrants based on the presence or lack of landmarks within each quadrant. The proposed pose descriptor is both effective and efficient, providing accurate yaw, pitch and roll axis estimates almost in real-time, without need for any training or previous knowledge about the subject. The experiments conducted on both the BIWI Kinect Head Pose Database and the challenging automated facial landmarks in the wild dataset, highlight a pose estimate precision exceeding the state-of-the-art with regard to methods not involving training and machine learning approaches.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/8717583

#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
 # focal_point: ""
 # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
