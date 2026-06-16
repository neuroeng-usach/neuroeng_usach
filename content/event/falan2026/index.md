---
title: "Interpretable machine learning of micro-ERG reveals muted retinal gain tracking in 5xFAD mice"
event: "IV FALAN Congress 2026"
event_url: "https://congress2026.neurocienciasfalan.org/"
location: "Centro de Extensión UC - Alameda"
address:
  street: "Av. Alameda Libertador Bernardo O'Higgins, 390"
  city: "Santiago"
  region: "Metropolitana"
  postcode: ""
  country: "Chile"
summary: "Presented a poster on using interpretable machine learning on micro-ERG signals to discriminate WT from 5xFAD retinas, identifying muted gain tracking as a key biomarker."
abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2026-08-31T09:00:00-04:00
date_end: 2026-09-03T18:00:00-04:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2026-06-16T19:42:54-04:00

authors:
  - leomedina
  - "Joel Villalobos"
  - adrianpalacios
  - "David B. Grayden"
  - "Joseph West"

projects: ["exploracion2022", "fondecyt2024"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags: ["Machine Learning", "micro-ERG", "5xFAD", "Retinal Gain Tracking", "Alzheimer's Disease", "Complexity"]
categories: []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Smart"

---

**Background.** Inexpensive, scalable biomarkers of early Alzheimer's disease (AD) remain an unmet need, and the retina, as a developmental enlargement of the central nervous system, may offer such a window. The 5xFAD mouse exhibits electrophysiologically detectable retinal alterations. We ask whether multi-electrode micro-electroretinogram (μERG) signals can discriminate wild-type (WT) from 5xFAD retinas, and whether deep-learning interpretability may guide the discovery of mechanistic features.

**Methods.** We recorded μERG from 23 WT and 23 5xFAD, across young and adult cohorts, using a 16x16 multi-electrode array under a 35-second chirp (flash, frequency, and amplitude sweeps) and a 10-second natural-image video. Under subject-disjoint 5-fold cross-validation with age-blind inputs, we compared three strategies: 1) 1-D convolutional neural networks (CNNs), 2) classical machine learning on hand-crafted (HC) features, and 3) multiscale-entropy complexity features.

**Results.** For chirp, HC with logistic regression reached a pooled area under the curve (AUC) of 0.735, complexity features 0.729, and CNN 0.590; for natural images, the values were 0.782, 0.736, and 0.752. Further, interpretability analyses, i.e., Grad-CAM, integrated gradients, virtual band blockade, and Bayesian input optimization, localized the CNN's cue to the amplitude-sweep fundamental-frequency gain trajectory, a pattern we term "muted gain tracking" in 5xFAD; encoding it as four additional features raised chirp AUC to 0.834, thereby surpassing the network.

**Conclusions.** Taken together, μERG signals carry a robust 5xFAD signature recoverable by machine learning, with compact, biologically-grounded features matching end-to-end deep learning; nevertheless, CNN interpretability translates modest performance into mechanistic markers, namely, retinal gain tracking, with promising translational potential as AD biomarkers.

**Financiamiento/Funding.** Becas Chile de Postdoctorado en el Extranjero; ANID Exploración 13220082; Fondecyt Regular 1241202.
