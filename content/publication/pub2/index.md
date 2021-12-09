---
title: "AFCNNet: Automated detection of AF using chirplet transform and deep convolutional bidirectional long short term memory network with ECG signals"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tejas Radhakrishnan
- admin
- Samit Kumar Ghosh
- PR Muduli
- Rajesh Kumar Tripathy
- U Rajendra Acharya

date: "2021-10-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.compbiomed.2021.104783"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computers in Biology and Medicine*
publication_short: In *CBM"

abstract: Atrial fibrillation (AF) is the most common type of cardiac arrhythmia and is characterized by the heart's beating in an uncoordinated manner. In clinical studies, patients often do not have visible symptoms during AF, and hence it is harder to detect this cardiac ailment. Therefore, automated detection of AF using the electrocardiogram (ECG) signals can reduce the risk of stroke, coronary artery disease, and other cardiovascular complications. In this paper, a novel time-frequency domain deep learning-based approach is proposed to detect AF and classify terminating and non-terminating AF episodes using ECG signals. This approach involves evaluating the time-frequency representation (TFR) of ECG signals using the chirplet transform. The two-dimensional (2D) deep convolutional bidirectional long short-term memory (BLSTM) neural network model is used to detect and classify AF episodes using the time-frequency images of ECG signals. The proposed TFR based 2D deep learning approach is evaluated using the ECG signals from three public databases. Our developed approach has obtained an accuracy, sensitivity, and specificity of 99.18% (Confidence interval (CI) as [98.86, 99.49]), 99.17% (CI as [98.85 99.49]), and 99.18% (CI as [98.86 99.49]), respectively, with 10-fold cross-validation (CV) technique to detect AF automatically. The proposed approach also classified terminating and non-terminating AF episodes with an average accuracy of 75.86%. The average accuracy value obtained using the proposed approach is higher than the short-time Fourier transform (STFT), discrete-time continuous wavelet transform (DT-CWT), and Stockwell transform (ST) based time-frequency analysis methods with deep convolutional BLSTM models to detect AF. The proposed approach has better AF detection performance than the existing deep learning-based techniques using ECG signals from the MIT-BIH database.

# Summary. An optional shortened abstract.
summary: We propose a novel time-frequency domain deep learning-based approach to detect and analyse Atrial Fibrilliation using ECG Signals.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://www.sciencedirect.com/science/article/abs/pii/S0010482521005771

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: 
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---