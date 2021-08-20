# Data Science Residency Project
## Ekim Luo
*Aug 20, 2021*

This project is based on the [nilearn example](https://nilearn.github.io/auto_examples/03_connectivity/plot_group_level_connectivity.html) on classifying age using functional connectivity. They found that tangent embedding was the best way to classify age groups based on functional connectivity. In this notebook, the same classifier is applied to [The Stockholm Sleepy Brain](https://openneuro.org/datasets/ds000201/versions/1.0.2) resting-state functional data, specifically to classify sex (female v. male) and age group (young v. old) with an increased test sample size (n = 10 instead of n = 5).  

### The Stockholm Sleepy Brain Project
The Stockholm Sleepy Brain project aimed to investigate the overall effect of sleepiness on emotional processing. See [Tamm et al. 2017](https://www.nature.com/articles/s41598-017-12098-9) for a paper produced from this dataset. 
- Version 1.0.2 (4.24.2019)
- Source: [OpenNeuro](https://openneuro.org/datasets/ds000201/versions/1.0.2/download)
- The dataset was downloaded using AWS. Only 38 subject folders are downloaded. 
