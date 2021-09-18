---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "lncLocator 2.0: a cell-line-specific subcellular localization predictor for long non-coding RNAs with interpretable deep learning"
authors: [admin, Xiao-Yong Pan, Hong-Bin Shen]
date: 2021-02-21T00:00:00+02:00
doi: "https://doi.org/10.1093/bioinformatics/btab127"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-21T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "Bioinformatics"
publication_short: ""

abstract: "In this study, we present an updated cell-line-specific predictor lncLocator 2.0, which trains an end-to-end deep model per cell line, for predicting lncRNA subcellular localization from sequences.We first construct benchmark datasets of lncRNA  subcellular localizations for 15 cell lines. Then we learn word embeddings using natural language models, and these learned embeddings are fed into convolutional neural network, long short-term memory and multilayer perceptron to classify subcellular localizations. lncLocator 2.0 achieves varying effectiveness for different cell lines and demonstrates the necessity of training cell-line-specific models. Furthermore, we adopt Integrated Gradients to explain the proposed model in lncLocator 2.0, and find some potential patterns that determine the subcellular localizations of lncRNAs, suggesting that the subcellular localization of lncRNAs is linked to some specific nucleotides."

# Summary. An optional shortened abstract.
summary: ""

tags: [Bioinformatics, Deep learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/Yang-J-LIN/lncLocator2
url_dataset:
url_poster:
url_project: http://www.csbio.sjtu.edu.cn/bioinf/lncLocator2/
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
slides: ""
---
