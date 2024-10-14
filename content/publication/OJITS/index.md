---
title: 'Multimodal Learning for Traffic Risk Prediction: Combining Aerial Imagery with Contextual Data'

authors:
  - Hanlin Tian
  - Yuxiang Feng
  - Mohammed Quddus
  - Yiannis Demiris
  - Panagiotis Angeloudis

doi: ''

# Publication type.
# 2 means journal paper, but you can change if submitting to a conference.
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Submitted to IEEE Open Journal of Intelligent Transportation Systems (OJ-ITS)'
publication_short: 'Submitted to OJ-ITS'

abstract: >
  Accurately predicting traffic risks at urban intersections is essential for improving road safety. While traditional models use data sources like road traffic conditions, geometry, and signals, they often miss the spatial interactions between road networks and buildings. This study introduces a multimodal deep learning framework that integrates aerial imagery, building footprint data, and traffic flow information to improve traffic risk prediction and better capture these complex relationships.

  By leveraging datasets from OpenStreetMap, the UK Traffic Count, and high-resolution aerial imagery, our approach creates a comprehensive representation of the urban environment, capturing intricate spatial relationships between road networks, surrounding structures, and traffic conditions. Using DeepLabV3+ and UNet++ as baseline models, we demonstrate that combining building and traffic data enhances prediction accuracy compared to models relying solely on visual data.

  Our results show that the DeepLabV3+ model, when incorporating both building and traffic data, achieves the highest Intersection over Union (IoU) score of 0.4052 and the lowest Root Mean Square Error (RMSE) of 0.0907. These findings underscore the effectiveness of a multimodal approach in traffic risk assessment, offering a more precise tool for urban planning and traffic management interventions. The code and data used in this study are available at [https://github.com/zachtian/Multimodal-Learning-for-Traffic-Risk-Prediction](https://github.com/zachtian/Multimodal-Learning-for-Traffic-Risk-Prediction).

tags: [Multimodal Learning, Traffic Risk Prediction, Aerial Imagery, Geographic Information Systems, Computer Vision]

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
links:
- name: Download Code and Data
  url: https://github.com/zachtian/Multimodal-Learning-for-Traffic-Risk-Prediction
links:
- name: Download PDF
  url: uploads/OJITS.pdf
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

---
