+++
title = "Automatically-extracted rhythm metrics can distinguish the presence, subtype, and severity of ataxic dysarthria"
date = 2026-02-25
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2026-02-25
time_end = 2026-02-25
all_day = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ben Parrell","Eugenia San Segundo" ]

# Abstract and optional shortened version.
abstract = ": Automatic detection and assessment of dysarthria using machine learning is an area of growing interest. However, relatively little attention has been paid to dysarthria in cerebellar ataxia (CA) and the little existing work in this area has focused on voice features. While vocal fold function is impaired in some individuals with CA, more consistent impairments are found in articulation and, in particular, in disruptions to speech rhythm. Here, we test whether automatically-extracted speech rhythm features can identify and characterize dysarthria in CA, including two clinically-identified subtypes of ataxic dysarthria: inflexibility and instability. Methods: 44 CA participants and 30 neurobiologically healthy (NH) age-matched controls performed an English-language version of the Bogenhausen Dysarthria Scales test, include spontaneous speech, sentence repetition, passage reading, and picture story narration as well as alternating and sequential diadochokinetic tasks. For each task, overlapping pause-free 1400-1600 ms windows were extracted, from which the spectrum of the amplitude envelope was calculated. Subsequently, several spectral features were derived that have previously been shown to be sensitive to rhythmic differences either in dysarthria speech or between languages in healthy speech: centroid, spread, roll-off, entropy, flatness, and the high-frequency (3.5-10 Hz) to low-frequency (<3.5 Hz) power ratio, with an average value for each each feature, for each task, calculated for each participant. Three Support Vector Machine (SVM) models were then built: 1) features that showed significant differences between CA and NH groups were used to distinguish these groups; 2) features correlated with dysarthria severity in CA (0-4, as rated by trained clinicians) were used to predict dysarthria severity; 3) features showing differences between the subtypes of ataxic dysarthria (combining mixed and inflexible groups to due the low numbers of individuals in each group) were used to predict subtype. Data were split 80%/20% for training/test, respectively, with 10-fold cross validation (5-fold for dysarthria subtype). Results: SVM models were able to reliably distinguish between CA and NH groups, with cross-validated model accuracies (AUCs) ranging from 71% using speech-only features and 82% using DDK-only features, to 96% using both classes of features. SVM models also well predicted dysarthria severity, with an R2 of 0.82 and cross-validated MSE of 0.39. Prediction accuracy for ataxic dysarthria subtype was slightly lower, but still relatively high, with a cross-validated accuracy of 0.81. Notably, identification of controls and the instable group in particular were highly consistent; the model also identified dysarthria in several “asymptomatic” CA individuals. Discussion: Automatically-extracted metrics of speech rhythm were highly effective at detecting CA and the subtype of dysarthria in CA, even in individuals with no clinical diagnosis of dysarthria, and were similarly effective in assessing the severity of dysarthria in this population. Consistent with clinical best-practice, combining analyses of DDK taks and speech production yields the most accurate classification. While future work will explore incorporating more sophisticated rhythm metrics as well as measures of phonation and articulation to fully characterize dysarthric impairments, these results hold promise for aiding clinical diagnosis and disease monitoring in individuals with CA."
abstract_short = ""

# Name of event and optional event URL.
event = "Twenty-second Biennial Conference on Motor Speech: Motor Speech Disorders & Speech Motor Control"
event_url = "https://www.madonna.org/motor-speech-conference"

# Location of event.
location = "Tempe, Arizona, United States"

# Is this a featured talk? (true/false)
featured = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
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
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
