+++
title = "Pulse Shape Discrimination and Exploration of Scintillation Signals Using Convolutional Neural Networks"
date = 2018-07-18

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. Griffiths", "S. Kleinegesse", "D. Saunders", "R. Taylor", "A. Vacheret"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "arXiv"
publication_short = ""

# Abstract.
abstract = "We demonstrate the use of a convolutional neural network to perform neutron-gamma pulse shape discrimination, where the only inputs to the network are the raw digitised SiPM signals from a dual scintillator detector element made of 6LiF:ZnS(Ag) scintillator and PVT plastic. A realistic labelled dataset was created to train the network by exposing the detector to an AmBe source, and a data-driven method utilsing a separate PMT was used to assign labels to the recorded signals. This approach is compared to the charge integration and continuous wavelet transform methods and is found to provide superior levels of discrimination, achieving an AUC of 0.995 +/- 0.003. We find that the neural network is capable of extracting interpretable features directly from the raw data. In addition, by visualising the high-dimensional representations of the network with the t-SNE algorithm, we discover that not only is this method robust to minor mislabeling of the training dataset but that it is possible to identify an underlying substructure within the signals that goes beyond the original labelling. This technique could be utilised to explore and cluster complex, raw detector data in a novel way that may reveal more insights than standard analysis methods."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1807.06853.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]
links = [{name = "Source", url = "https://arxiv.org/abs/1807.06853"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
