---
title: 'An End-to-End Collaborative Learning Approach for Connected Autonomous Vehicles in Occluded Scenarios'

authors:
  - Leandro Parada
  - Hanlin Tian
  - Jose Escribano
  - Panagiotis Angeloudis

date: '2023-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE 26th International Conference on Intelligent Transportation Systems
publication_short: In ITSC 2023

abstract: Collaborative navigation becomes essential in situations of occluded scenarios in autonomous driving where independent driving policies are likely to lead to collisions. One promising approach to address this issue is through the use of Vehicle-to-Vehicle (V2V) networks that allow for the sharing of perception information with nearby agents, preventing catastrophic accidents. In this article, we propose a collaborative control method based on a V2V network for sharing compressed LiDAR features and employing Proximal Policy Optimisation to train safe and efficient navigation policies. Unlike previous approaches that rely on expert data (behaviour cloning), our proposed approach learns the multi-agent policies directly from experience in the occluded environment, while effectively meeting bandwidth limitations. The proposed method first prepossesses LiDAR point cloud data to obtain meaningful features through a convolutional neural network and then shares them with nearby CAVs to alert for potentially dangerous situations. To evaluate the proposed method, we developed an occluded intersection gym environment based on the CARLA autonomous driving simulator, allowing real-time data sharing among agents. Our experimental results demonstrate the consistent superiority of our collaborative control method over an independent reinforcement learning method and a cooperative early fusion method.

tags: [Autonomous Vehicle]

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

---
