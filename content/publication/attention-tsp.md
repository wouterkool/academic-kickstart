+++
title = "Attention Solves Your TSP"
date = 2018-03-23T16:52:55+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wouter Kool", "Max Welling"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "arXiv preprint"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We propose a framework for solving combinatorial optimization problems of which the output can be represented as a sequence of input elements. As an alternative to the Pointer Network, we parameterize a policy by a model based entirely on (graph) attention layers, and train it efficiently using REINFORCE with a simple and robust baseline based on a deterministic (greedy) rollout of the best policy found during training. We significantly improve over state-of-the-art results for learning algorithms for the 2D Euclidean TSP, reducing the optimality gap for a single tour construction by more than 75% (to 0.33%) and 50% (to 2.28%) for instances with 20 and 50 nodes respectively."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "tsp_preview.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1803.08475"
url_code = "https://github.com/wouterkool/attention-tsp"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "tsp_header.png"
caption = ""

+++
