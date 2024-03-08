---
title: 'Bézier Everywhere All at Once: Learning Drivable Lanes as Bézier Graphs'

authors:
  - Hugh Blayney
  - Hanlin Tian
  - Hamish Scott
  - Nils Goldbeck
  - Chess Stetson
  - Panagiotis Angeloudis

date: '2024-02-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Conference on Computer Vision and Pattern Recognition 2024
publication_short: In CVPR 2024

abstract: Knowledge of lane topology is a core problem in autonomous driving. Vision-based techniques hold the promise of automatically detecting everything the human eye can see, like roadlines. Aerial imagery in particular can provide high resolution, quickly updatable, occlusion-free source data.  Yet so far, detecting lanes from such data has been an expensive manual process or, where automated solutions exist, undrivable and requiring of downstream processing. In this paper we propose a method for large-scale lane topology extraction from aerial imagery. Our method ensures that the resulting lanes are realistic and drivable by representing them using shared parameterisation of Béezier curves. We propose a novel method of fitting a Bézier Graph of shared Bézier curves to an arbitrary lane network and develop a transformer-based model to generate these Béezier Graphs from input aerial images. We achieve competitive results on the Urban Lane Graph dataset, and further demonstrate that our method generates realistic lane graphs which require both minimal input, and minimal downstream processing.

tags: [Autonomous Vehicle, Computer Vision]

# Display this page in the Featured widget?
featured: True

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
