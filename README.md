
Animal Vocalization Generative Network (AVGN)
==============================

This is a project for taking animal vocalization audio recordings, and learning a generative model of segments of those vocalizations (e.g. syllables) using modern machine learning techniques. Specifically. This package will take in a dataset of wav files, segment them into units (e.g. syllables of birdsong) and train a generative model on those segments. The learned latent representations can be used to cluster syllables in an unsupervised manner, generate novel syllables, visualize sequences, or perform several other analyses.

---


![description](src_img/animalvocalizationfigure.png)


Documentation
------------
Examples of of different songbirds are located in the 'notebooks/birdsong' folder. There is no explicit documentation, but we will work on adding better docstrings to different functions, and adding more notes to the example notebooks. 

Currently there are two example birds - Cassins vireo, and Bengalese finch. The Cassin's vireo example dataset compares hand labelled syllables to syllable labels learned using out method, and thus uses the same segmentations as the manual method. The Bengalese finch is segmented automatically. 

Installation
------------

to install run python `setup.py install`

---

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>


Data references
------------

Hedley, Richard (2016): Data used in PLoS One article “Complexity, Predictability and Time Homogeneity of Syntax in the Songs of Cassin’s Vireo (Vireo cassini)” by Hedley (2016). figshare. https://doi.org/10.6084/m9.figshare.3081814.v1

Katahira K, Suzuki K, Kagawa H, Okanoya K (2013) A simple explanation for the evolution of complex song syntax in Bengalese finches. Biology Letters 9(6): 20130842. https://doi.org/10.1098/rsbl.2013.0842  https://datadryad.org//resource/doi:10.5061/dryad.6pt8g

Katahira K, Suzuki K, Kagawa H, Okanoya K (2013) Data from: A simple explanation for the evolution of complex song syntax in Bengalese finches. Dryad Digital Repository. https://doi.org/10.5061/dryad.6pt8g

Arriaga, J. G., Cody, M. L., Vallejo, E. E., & Taylor, C. E. (2015). Bird-DB: A database for annotated bird song sequences. Ecological informatics, 27, 21-25. http://taylor0.biology.ucla.edu/birdDBQuery/

