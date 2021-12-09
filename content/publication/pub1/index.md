---
title: "An example conference paper"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Samit Kumar Ghosh
- Pranjali Gajbhiye
- Rajesh Kumar Tripathy
- U Rajendra Acharya

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-08-01T00:00:00Z"
doi: "https://doi.org/10.3390/app11177920"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Applied Sciences*
publication_short: In *Applied Sciences"

abstract: Myocardial infarction (MI) occurs due to the decrease in the blood flow into one part of the heart, and it further causes damage to the heart muscle. The 12-channel electrocardiogram (ECG) has been widely used to detect and localize MI pathology in clinical studies. The vectorcardiogram (VCG) is a 3-channel recording system used to measure the heart’s electrical activity in sagittal, transverse, and frontal planes. The VCG signals have advantages over the 12-channel ECG to localize posterior MI pathology. Detection and localization of MI using VCG signals are vital in clinical practice. This paper proposes a multi-channel multi-scale two-stage deep-learning-based approach to detect and localize MI using VCG signals. In the first stage, the multivariate variational mode decomposition (MVMD) decomposes the three-channel-based VCG signal beat into five components along each channel. The multi-channel multi-scale VCG tensor is formulated using the modes of each channel of VCG data, and it is used as the input to the deep convolutional neural network (CNN) to classify MI and normal sinus rhythm (NSR) classes. In the second stage, the multi-class deep CNN is used for the categorization of anterior MI (AMI), anterior-lateral MI (ALMI), anterior-septal MI (ASMI), inferior MI (IMI), inferior-lateral MI (ILMI), inferior-posterior-lateral (IPLMI) classes using MI detected multi-channel multi-scale VCG instances from the first stage. The proposed approach is developed using the VCG data obtained from a public database. The results reveal that the approach has obtained the accuracy, sensitivity, and specificity values of 99.58%, 99.18%, and 99.87%, respectively, for MI detection. Moreover, for MI localization, we have obtained the overall accuracy value of 99.86% in the second stage for our proposed network. The proposed approach has demonstrated superior classification performance compared to the existing VCG signal-based MI detection and localization techniques. View Full-Text

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://www.mdpi.com/2076-3417/11/17/7920

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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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

#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
