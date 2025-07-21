+++
title = "A Novel Focal Tversky loss function with improved Attention U-Net for lesion segmentation"
date = "2019-04-09"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Nabila Abraham**","Naimul Mefraz Khan"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "International Symposium on Biomedical Imaging."
#publication_short = "ISBI"

# Abstract and optional shortened version.

#abstract = "We propose a generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation. Compared to the commonly used Dice loss, our loss function achieves a better trade off between precision and recall when training on small structures such as lesions. To evaluate our loss function, we improve the attention U-Net model by incorporating an image pyramid to preserve contextual features. We experiment on the BUS 2017 dataset and ISIC 2018 dataset where lesions occupy 4.84% and 21.4% of the images area and improve segmentation accuracy when compared to the standard U-Net by 25.7% and 3.6%, respectively."

abstract = "A generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation."

# Featured image thumbnail (optional)
image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "/files/0542.pdf"
url_preprint = "https://arxiv.org/abs/1810.07842"
url_code = "https://github.com/nabsabraham/focal-tversky-unet"
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
A generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation.

In *International Symposium on Biomedical Imaging*, 2019. 
**Oral**.
