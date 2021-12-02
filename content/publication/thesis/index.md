---
abstract: 'This thesis examines the application of machine learning pipelines for automatic generalised seizure detection. We begin by introducing the potential pipeline components of a signal classification system (Pre-processing, Feature Engineering, Dimensionality Reduction, and Classification), and review the literature associated with each stage. In the subsequent research chapters, Bayesian optimisation is used to systematically optimise many pipeline/model configurations and hyperparameters to provide practical guidance and inform future pipeline development. There is a focus on ecological validity, therefore we use real-world "raw" patient records collected as part of routine care from multiple healthcare institutions. In chapter 3, using a large feature set and feature reduction techniques, we were able to identify components of EEG records useful for identifying absence epilepsy seizures
for pipelines with "classical" classifiers. These pipelines had good overall performance, at the expense of a high false positive rate (FPR); with the best binary classifiers never missing a seizure and accurately marking the full duration of most seizures. As class imbalances were a challenge for effective model training, chapter 4 examined pipelines with balanced ensemble classifiers. Compared to chapter 3, boosted ensembles were faster, with a lower FPR and high precision/specificity. However, typically the full seizure was not marked, meaning they may be more useful for accessing the number of seizures in a record rather than their length. Subsequently, chapter 5 examined the performance of boosted ensembles and deep learning architectures on two different types of generalised seizure. Consistent with human raters, models trained to detect absence seizures, a seizure type with little intra-patient and inter-patient variability, had better performance across all investigated metrics compared to non-specific seizures, which have large intra-patient and inter-patient variabilities. Compared to deep learning models, boosted ensembles provided the best overall performance, were more computationally-efficient, and would be easier to implement into healthcare practice. To our knowledge, this thesis provides the first use of optimal hyperparameters and pipeline components found through Bayesian optimisation methods for absence epilepsy detection. In the future, such pipelines could reduce the current bottleneck of clinical time required to manually mark EEG records by providing a preliminary marked record to a physiologist.'
authors:
- admin
date: "2021-06-17T00:00:00Z"
doi: "10.17635/lancaster/thesis/1347"
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false
projects:
- internal-project
publication: Lancaster University
publication_short: ""
publication_types:
- "7"
publishDate: "2017-01-01T00:00:00Z"
slides: 
summary: This thesis examines the application of machine learning pipelines for automatic generalised seizure detection.
tags:
- Machine Learning
- EEG
- Seizure
title: Automatic Generalised Seizure Detection in Clinical Electroencephalography Records
url_code: ""
url_dataset: ""
url_pdf: http://www.research.lancs.ac.uk/portal/services/downloadRegister/329483401/2021davidelliottphd.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
