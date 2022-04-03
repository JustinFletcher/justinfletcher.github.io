---
layout: essay  
type: essay  
title: Evidence of Scholarly Ability  
date: 2019-02-18
labels:
  - PhD Portfolio
---

*This page presents evidence of my scholarly ability in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). This includes evidence of ability to identify, critically analyze, and research a problem, as well as written communication skills.*

## Publications

For a quantitiative assessment of the impact of my recent work, please see my [Google Scholar author page](https://scholar.google.com/citations?hl=en&user=YSEl3usAAAAJ&view_op=list_works). 

TODO: SPIE DCS 2022

TODO: IEEE Aero 2022

*Learned Event-Based Visual Perception for Improved Space Object Detection*. N. Salvatore, J. Fletcher, 
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2022) (2022).

Abstract: The detection of dim artificial Earth satellites using ground-based electro-optical sensors, particularly in the presence of background light, is technologically challenging. This perceptual task is foundational to our understanding of the space environment, and grows in importance as the number, variety, and dynamism of space objects increases. We present a hybrid image-and event-based architecture that leverages dynamic vision sensing technology to detect resident space objects in geosynchronous Earth orbit. Given the asynchronous, one-dimensional image data supplied by a dynamic vision sensor, our architecture applies conventional image feature extractors to integrated, two-dimensional frames in conjunction with point-cloud feature extractors, such as PointNet, in order to increase detection performance for dim objects in scenes with high background activity. In addition, an end-to-end event-based imaging simulator is developed to both produce data for model training as well as approximate the optimal sensor parameters for event-based sensing in the context of electro-optical telescope imagery. Experimental results confirm that the inclusion of point-cloud feature extractors increases recall for dim objects in the high-background regime.

Contributions: My contributions to this paper include the formulation of event-based sensning concept for satellite detection, direct supervision of the development of the model architecture, and the model evaluation criteria, as well as co-authorship of the text.

[Full Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Salvatore_Learned_Event-Based_Visual_Perception_for_Improved_Space_Object_Detection_WACV_2022_paper.pdf)


*SpectraNet: Learned Recognition of Artificial Satellites From High Contrast Spectroscopic Imagery*. J. Z. Gazak, I. McQuaid, R. Swindle, M. Phelps, J. Fletcher
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2022) (2022).

Abstract: Effective space traffic management requires positive identification of artificial satellites. Current methods for extracting object identification from observed data require spatially resolved imagery which limits identification to objects in low earth orbits. Most artificial satellites, however, operate in geostationary orbits at distances which prohibit ground based observatories from resolving spatial information. This paper demonstrates an object identification solution leveraging modified residual convolutional neural networks to map distance-invariant spectroscopic data to object identity. We report classification accuracies exceeding 80% for a simulated 64-class satellite problem--even in the case of satellites undergoing constant, random re-orientation. An astronomical observing campaign driven by these results returned accuracies of 72% for a nine-class problem with an average of 100 examples per class, performing as expected from simulation. We demonstrate the application of variational Bayesian inference by dropout, stochastic weight averaging (SWA), and SWA-focused deep ensembling to measure classification uncertainties--critical components in space traffic management where routine decisions risk expensive space assets and carry geopolitical consequences.

Contributions: My contributions to this work include the orginal formulation of the satellite spectral recognition problem and direct supervision of all aspects of the work, excluding astronomical observations and instrument restoration.

[Full Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Gazak_SpectraNet_Learned_Recognition_of_Artificial_Satellites_From_High_Contrast_Spectroscopic_WACV_2022_paper.pdf)


*Self-Attending Task Generative Adversarial Network for Realistic Satellite Image Creation*. N. Toner, J. Fletcher, 
IEEE Aerospace Conference 2022 (2022).

Abstract: We introduce a self-attending task generative adversarial network (SATGAN) and apply it to the problem of augmenting synthetic high contrast scientific imagery of resident space objects with realistic noise patterns and sensor characteristics learned from collected data. Augmenting these synthetic data is challenging due to the highly localized nature of semantic content in the data that must be preserved. Real collected images are used to train a network what a given class of sensor's images should look like. The trained network then acts as a filter on noiseless context images and outputs realistic-looking fakes with semantic content unaltered. The architecture is inspired by conditional GANs but is modified to include a task network that preserves semantic information through augmentation. Additionally, the architecture is shown to reduce instances of hallucinatory objects or obfuscation of semantic content in context images representing space observation scenes.

Contributions: This work was supported under an Air Force Office of Scientific Research grant, for which I was the PI. I developed the task, provided the first implementaion of the model architecture described in this work, directly supervised subsequent efforts, and coauthered the paper.

[Full Paper](https://arxiv.org/pdf/2111.09463)









*title*. N Author, M Authors, 
Longconferencetitile (ACRO YEAR) (YEAR).

Abstract: text

Contributions: 

[Full Paper](link)


## Literature Review

*Reinforcment Learning for Optical System Control: A Literature Review*
Abstract: To image 
Justin Fletcher.
[Full Paper](https://justinfletcher.github.io/_data/lit_review.pdf)
