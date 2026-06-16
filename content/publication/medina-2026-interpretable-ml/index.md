---
title: "Interpretable machine learning of micro-ERG reveals muted retinal gain tracking in 5xFAD mice"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- leomedina
- "Joel Villalobos"
- adrianpalacios
- "David B. Grayden"
- "Joseph West"

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-06-16T19:42:54Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 'In *IV FALAN Congress 2026*'
publication_short: ''

doi: '10.32372/4ID-JP957HB'

abstract: 'Background. Inexpensive, scalable biomarkers of early Alzheimer’s disease (AD) remain an unmet need, and the retina, as a developmental enlargement of the central nervous system, may offer such a window. The 5xFAD mouse exhibits electrophysiologically detectable retinal alterations. We ask whether multi-electrode micro-electroretinogram (μERG) signals can discriminate wild-type (WT) from 5xFAD retinas, and whether deep-learning interpretability may guide the discovery of mechanistic features. Methods. We recorded μERG from 23 WT and 23 5xFAD, across young and adult cohorts, using a 16x16 multi-electrode array under a 35-second chirp (flash, frequency, and amplitude sweeps) and a 10-second natural-image video. Under subject-disjoint 5-fold cross-validation with age-blind inputs, we compared three strategies: 1) 1-D convolutional neural networks (CNNs), 2) classical machine learning on hand-crafted (HC) features, and 3) multiscale-entropy complexity features. Results. For chirp, HC with logistic regression reached a pooled area under the curve (AUC) of 0.735, complexity features 0.729, and CNN 0.590; for natural images, the values were 0.782, 0.736, and 0.752. Further, interpretability analyses, i.e., Grad-CAM, integrated gradients, virtual band blockade, and Bayesian input optimization, localized the CNN’s cue to the amplitude-sweep fundamental-frequency gain trajectory, a pattern we term "muted gain tracking" in 5xFAD; encoding it as four additional features raised chirp AUC to 0.834, thereby surpassing the network. Conclusions. Taken together, μERG signals carry a robust 5xFAD signature recoverable by machine learning, with compact, biologically-grounded features matching end-to-end deep learning; nevertheless, CNN interpretability translates modest performance into mechanistic markers, namely, retinal gain tracking, with promising translational potential as AD biomarkers.'

# Summary. An optional shortened abstract.
summary: ''

tags: ["Machine Learning", "micro-ERG", "5xFAD", "Retinal Gain Tracking", "Alzheimer's Disease", "Complexity"]

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["exploracion2022", "fondecyt2024"]

links:
- name: DOI
  url: https://doi.org/10.32372/4ID-JP957HB
---

### Funding
Becas Chile de Postdoctorado en el Extranjero; ANID Exploración 13220082; Fondecyt Regular 1241202.
