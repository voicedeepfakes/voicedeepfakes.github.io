+++
title = "Beyond the black box: Explainable deepfake detection through prosodic analysis of the Spanish discourse marker «¿no?»"
date = 2026-08-16T21:11:38+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Blanca Hernández", "Jonathan Delgado", "Eugenia San Segundo"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Normas. Revista de estudios lingüísticos hispánicos*, 16 (1), pp. 1–20"
publication_short = ""

# Abstract and optional shortened version.
abstract = "The increasing sophistication of audio deepfake generation by current algorithms compounds the difficulty of developing models capable of distinguishing between human and synthetic speech, one of the foremost challenges in contemporary forensic phonetics. Despite the widespread use of end-to-end detection systems, handcrafted feature-based models remain valuable due to their greater explainability and reduced opacity. The present work explores the use of high-level acoustic-prosodic features (mean F0, dynamic F0 contour, and duration) as linguistically interpretable correlates that allow, on the one hand, an assessment of the importance of incorporating the suprasegmental component into deepfake detection models and, on the other, the interpretation of results on forensic grounds. Focusing on the Spanish discourse marker ¿no?, we extracted 14 prosodic variables from 272 tokens drawn from the VoxCeleb-ESP spontaneous speech corpus and their zero-shot cloned counterparts generated with the Qwen TTS system. Following Elastic Net feature selection, we trained six supervised machine learning classifiers and demonstrate that a Random Forest model achieves an AUC of 0.948 and an F1-score of 87.8% on an independent validation set. The results show that cloned voices systematically exaggerate the final portion of the marker’s intonation contour, producing a markedly higher pitch target. Furthermore, statistical models reveal that the duration of cloned audio samples is significantly longer (p < 0.009) than that of their bonafide counterparts. These findings are attributed to a read-speech bias in the cloning model’s training data. It is therefore concluded that further exploration of discourse markers and suprasegmental variables in forensic deepfake detection contexts is well warranted"
abstract_short = ""

# Is this a featured publication? (true/false)
featured = true

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

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://turia.uv.es/index.php/normas/es/article/view/34181"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
 url_custom = [{name = "Link", url = "https://turia.uv.es/index.php/normas/es/article/view/34181"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
