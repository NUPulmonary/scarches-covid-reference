# Reference-based analysis of bronchoalveolar lavage fluid single-cell data from COVID-19 patients

Here we explore the possibility of using [scArches](https://www.biorxiv.org/content/10.1101/2020.07.16.205997v1) (Lotfollahi et al., 2020) 
to build a reference single-cell dataset of bronchoalveolar lavage (BAL) fluid from patients with COVID-19 and use it to analyse other BAL samples.

As reference dataset we used samples from COVID-positive patients 
from [Grant et al., 2020](https://www.biorxiv.org/content/10.1101/2020.08.05.238188v2) and as a query dataset we used 
COVID-negative samples from the same preprint. Both datasets have published cell type annotations 
which we used to assess scArches performance at capturing biological variability in its latent space and at predicting cell type labels.

All the analysis is here https://nbviewer.jupyter.org/github/NUPulmonary/scarches-covid-reference/blob/master/main.ipynb

Dependencies for this exploration are managed by [pipenv](https://pipenv.pypa.io/en/latest/)

**Acknoledgements**\
This analysis wouldn't have been possible without help from Mohammad Lotfollahi (https://github.com/M0hammadL), Alexander Misharin (https://github.com/amisharin) and 
all the teams behind scArches project and Grant et al., 2020 preprint.
