---
title: "A LSTM-based approach for modelling the movement uncertainty of indoor trajectories with mobile sensing data"

authors:
- admin
- Wenzhong Shi
- Yue Yu
- Pengfei Chen
- Bi Yu Chen

# author_notes:
# - "Equal contribution"
# - "Equal contribution"



date: "2022-03-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Applied Earth Observations and Geoinformation*"
publication_short: "*International Journal of Applied Earth Observations and Geoinformation*"



abstract:  Individuals’ indoor trajectories can be reconstructed with sensing data for indoor navigation. However, the movement uncertainty of such reconstructed indoor trajectories has seldom been modelled before, which seriously affects the reliability of indoor trajectory analytics. Previous methods for movement uncertainty modelling mainly focus on outdoor trajectories, and are based on various user-specified assumptions, which may not hold effective for indoor environments and hence introduce inaccuracy in determining sizes of uncertain regions for indoor trajectories. To address above challenge, this research formulates uncertainty modelling of indoor trajectories as a sequence prediction problem and proposes a novel data-driven method. We construct input features by considering each step’s stride and heading angle. The constructed features are input into a LSTM-based neural network, and pointwise deviations of trajectories are predicted. Our model is data-driven and can learn the unknow mapping from each step’s feature to its corresponding uncertainty via neural network training, thus avoiding errors introduced by inaccurate assumptions of previous methods. We conduct experiments with real-world datasets, and demonstrate our method robustly outperforms previous models, regarding balancing preciseness (over 0.15/m2 density of covered ground-truth points) and completeness (over 80% ground-truth trajectory coverage). This paper provides a novel approach for generating uncertain regions by predicting pointwise deviations, and can benefit related applications of trajectory mining.



# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0303243422000848#!
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example



# {{% alert note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /alert %}}

# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}

# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).


---


