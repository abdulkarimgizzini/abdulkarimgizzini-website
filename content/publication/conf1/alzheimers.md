+++
title = "Transfer Learning With Intelligent Training Data Selection for Prediction of Alzheimer’s Disease"
date = "2019-06-03"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["Naimul Mefraz Khan", "**Nabila Abraham**", "Marcia Hon"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE Access."
#publication_short = "ISBI"

# Abstract and optional shortened version.

#abstract = "We propose a generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation. Compared to the commonly used Dice loss, our loss function achieves a better trade off between precision and recall when training on small structures such as lesions. To evaluate our loss function, we improve the attention U-Net model by incorporating an image pyramid to preserve contextual features. We experiment on the BUS 2017 dataset and ISIC 2018 dataset where lesions occupy 4.84% and 21.4% of the images area and improve segmentation accuracy when compared to the standard U-Net by 25.7% and 3.6%, respectively."

abstract = "We utilize transfer learning on the ADNI dataset, reduced in sample size by entropy selection to acheive state-of-the-art performance in multi-task classification. We provide a detailed analysis using class activation maps to demonstrate the model's performance on neuropathological regions that are task-relevant and can help healthcare practicioners in interpreting the model's decision."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://ieeexplore-ieee-org.ezproxy.lib.ryerson.ca/document/8727911"
url_preprint = ""
url_code = "https://github.com/nabsabraham/alzheimers"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
#name = "Journal"
#url = "https://link.springer.com/article/10.1007/s10584-014-1174-4"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "ftl.png"
#caption = "My caption :smile:"

+++
A data-driven method to reduce training sample size to mitigate careful model tuning required when using transfer learning for Alzheimer's disease classification.  

In *IEEE Access*, 2019. 

