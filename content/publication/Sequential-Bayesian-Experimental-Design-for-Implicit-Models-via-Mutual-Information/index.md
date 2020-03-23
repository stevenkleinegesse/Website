+++
title = "Sequential Bayesian Experimental Design for Implicit Models via Mutual Information"
date = 2020-03-20

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [Steven Kleinegesse, Christopher Drovandi, Michael U. Gutmann]

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
abstract = "Bayesian experimental design (BED) is a framework that uses statistical models and decision making under uncertainty to optimise the cost and performance of a scientific experiment. Sequential BED, as opposed to static BED, considers the scenario where we can sequentially update our beliefs about the model parameters through data gathered in the experiment. A class of models of particular interest for the natural and medical sciences are implicit models, where the data generating distribution is intractable, but sampling from it is possible. Even though there has been a lot of work on static BED for implicit models in the past few years, the notoriously difficult problem of sequential BED for implicit models has barely been touched upon. We address this gap in the literature by devising a novel sequential design framework for parameter estimation that uses the Mutual Information (MI) between model parameters and simulated data as a utility function to find optimal experimental designs, which has not been done before for implicit models. Our approach uses likelihood-free inference by ratio estimation to simultaneously estimate posterior distributions and the MI. During the sequential BED procedure we utilise Bayesian optimisation to help us optimise the MI utility. We find that our framework is efficient for the various implicit models tested, yielding accurate parameter estimates after only a few iterations."

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
url_pdf = "https://arxiv.org/pdf/2003.09379.pdf"
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
links = [{name = "Source", url = "https://arxiv.org/abs/2003.09379"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
