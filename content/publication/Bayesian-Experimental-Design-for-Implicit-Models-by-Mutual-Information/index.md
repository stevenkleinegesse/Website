+++
title = "Bayesian Experimental Design for Implicit Models by Mutual Information"
date = 2020-02-19

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Steven Kleinegesse", "Michael U. Gutmann"]

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
abstract = "Implicit stochastic models, where the data-generation distribution is intractable but sampling is possible, are ubiquitous in the natural sciences. The models typically have free parameters that need to be inferred from data collected in scientific experiments. A fundamental question is how to design the experiments so that the collected data are most useful. The field of Bayesian experimental design advocates that, ideally, we should choose designs that maximise the mutual information (MI) between the data and the parameters. For implicit models, however, this approach is severely hampered by the high computational cost of computing posteriors and maximising MI, in particular when we have more than a handful of design variables to optimise. In this paper, we propose a new approach to Bayesian experimental design for implicit models that leverages recent advances in neural MI estimation to deal with these issues. We show that training a neural network to maximise a lower bound on MI allows us to jointly determine the optimal design and the posterior. Simulation studies illustrate that this gracefully extends Bayesian experimental design for implicit models to higher design dimensions."

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
url_pdf = "https://arxiv.org/pdf/2002.08129.pdf"
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
links = [{name = "Source", url = "https://arxiv.org/abs/2002.08129"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
