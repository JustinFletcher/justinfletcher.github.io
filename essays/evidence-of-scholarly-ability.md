---
layout: essay  
type: essay  
title: Evidence of Scholarly Ability  
date: 2022-03-04
labels:
  - PhD Portfolio
---

*This page presents evidence of my scholarly ability in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). This includes evidence of ability to identify, critically analyze, and research a problem, as well as written communication skills.*

## Publications

I have included below only papers published since January 1st, 2021. For a complete list of prior work please see my [Google Scholar author page](https://scholar.google.com/citations?hl=en&user=YSEl3usAAAAJ&view_op=list_works). For prior work in which I am not the first author, my contributions always include direct supervision of the project. Supervision, here, means directly and routinely adivsing the author on the techncial execution of the project. I am not listed as a coauthor for projects in which my only involvement is managment of the executing personnel. 


*Towards jointly learned control policies and image recovery for distributed aperture telescopes*. Justin Fletcher, Peter Sadowski.
Presented, SPIE Defense and Commercial Sensing 2022 (SPIE DCS 2022) (2022).

Abstract: 
Extended object imaging of resident space objects is foundational to space domain awareness. Large aperture optical systems can capture spatially resolved imagery of objects in low Earth orbit but are infeasible for objects at higher altitudes. In this work we explore the application of distributed aperture optical systems to extended object imaging at distances beyond low Earth orbit using fully differentiable physical models. Distributed aperture systems are a cost-effective design for large aperture telescopes, but entail a sequential control problem to correct for aberrations induced by phase differences between the spatially distal subapertures. We provide a fully differentiable, joint formulation of this control problem and the associated image recovery task, and train a model to maximize reconstruction quality from an ensemble of focal plane images. We measure the quality of the recovered images, and position these results relative to the recovery quality achieved by monolithic telescopes.

[Full Paper](https://justinfletcher.github.io/_data/Towards_learned_control_policies_for_extended_object_imaging_using_distributed_aperture_telescopes__SPIE___Defense_and_Commercial_Sensing_2022_20220326_1618hst_jrf.pdf)


*Learned Event-Based Visual Perception for Improved Space Object Detection*. Nikolaus Salvatore, Justin Fletcher.
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2022) (2022).

Abstract: The detection of dim artificial Earth satellites using ground-based electro-optical sensors, particularly in the presence of background light, is technologically challenging. This perceptual task is foundational to our understanding of the space environment, and grows in importance as the number, variety, and dynamism of space objects increases. We present a hybrid image-and event-based architecture that leverages dynamic vision sensing technology to detect resident space objects in geosynchronous Earth orbit. Given the asynchronous, one-dimensional image data supplied by a dynamic vision sensor, our architecture applies conventional image feature extractors to integrated, two-dimensional frames in conjunction with point-cloud feature extractors, such as PointNet, in order to increase detection performance for dim objects in scenes with high background activity. In addition, an end-to-end event-based imaging simulator is developed to both produce data for model training as well as approximate the optimal sensor parameters for event-based sensing in the context of electro-optical telescope imagery. Experimental results confirm that the inclusion of point-cloud feature extractors increases recall for dim objects in the high-background regime.

Contributions: My contributions to this paper include the formulation of event-based sensning concept for satellite detection, direct supervision of the development of the model architecture, and the model evaluation criteria, as well as co-authorship of the text.

[Full Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Salvatore_Learned_Event-Based_Visual_Perception_for_Improved_Space_Object_Detection_WACV_2022_paper.pdf)


*SpectraNet: Learned Recognition of Artificial Satellites From High Contrast Spectroscopic Imagery*. Zach Gazak, Ian McQuaid, Ryan Swindle, Matthew Phelps, Justin Fletcher.
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV 2022) (2022).

Abstract: Effective space traffic management requires positive identification of artificial satellites. Current methods for extracting object identification from observed data require spatially resolved imagery which limits identification to objects in low earth orbits. Most artificial satellites, however, operate in geostationary orbits at distances which prohibit ground based observatories from resolving spatial information. This paper demonstrates an object identification solution leveraging modified residual convolutional neural networks to map distance-invariant spectroscopic data to object identity. We report classification accuracies exceeding 80% for a simulated 64-class satellite problem--even in the case of satellites undergoing constant, random re-orientation. An astronomical observing campaign driven by these results returned accuracies of 72% for a nine-class problem with an average of 100 examples per class, performing as expected from simulation. We demonstrate the application of variational Bayesian inference by dropout, stochastic weight averaging (SWA), and SWA-focused deep ensembling to measure classification uncertainties--critical components in space traffic management where routine decisions risk expensive space assets and carry geopolitical consequences.

Contributions: My contributions to this work include the orginal formulation of the satellite spectral recognition problem and direct supervision of all aspects of the work, excluding astronomical observations and instrument restoration.

[Full Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Gazak_SpectraNet_Learned_Recognition_of_Artificial_Satellites_From_High_Contrast_Spectroscopic_WACV_2022_paper.pdf)


*Self-Attending Task Generative Adversarial Network for Realistic Satellite Image Creation*. Nathan Toner, Justin Fletcher.
IEEE Aerospace Conference 2022 (2022).

Abstract: We introduce a self-attending task generative adversarial network (SATGAN) and apply it to the problem of augmenting synthetic high contrast scientific imagery of resident space objects with realistic noise patterns and sensor characteristics learned from collected data. Augmenting these synthetic data is challenging due to the highly localized nature of semantic content in the data that must be preserved. Real collected images are used to train a network what a given class of sensor's images should look like. The trained network then acts as a filter on noiseless context images and outputs realistic-looking fakes with semantic content unaltered. The architecture is inspired by conditional GANs but is modified to include a task network that preserves semantic information through augmentation. Additionally, the architecture is shown to reduce instances of hallucinatory objects or obfuscation of semantic content in context images representing space observation scenes.

Contributions: This work was supported under an Air Force Office of Scientific Research grant, for which I was the PI. I developed the task, provided the first implementaion of the model architecture described in this work, directly supervised subsequent efforts, and coauthered the paper.

[Full Paper](https://arxiv.org/pdf/2111.09463)


*Enhanced Image Reconstruction with Quality-Weighted Iterative Deconvolution (QWID)*. Michael Werth, Trent Kyono, Jacob Lucas, Ian McQuaid, Justin Fletcher. 
IEEE Aerospace Conference 2021 (2021).

Abstract: Multi-frame blind deconvolution (MFBD) algorithms are able to produce high-resolution image reconstructions from severely degraded inputs. Often these algorithms are designed with a number of assumptions about the observing scenario and the data quality, and when these assumptions are violated the reconstruction quality can suffer. However, it can be challenging to automatically assign quality scores to input images for data rejection, especially while observing Low Earth Orbit (LEO) satellites through the turbulent atmosphere as they transit across a large patch of the sky. We report on an algorithm that uses a convolutional neural network (CNN) to assign quality scores to images prior to MFBD processing in a system titled Quality-Weighted Iterative Deconvolution (QWID). This quality assessment represents the likelihood that each input frame can contribute meaningful signal to the frame reconstruction process. The neural network is trained on a simulated dataset of ground-based observations of LEO satellites, where true quality is known. Improvements in performance over the same MFBD implementation in the absence of quality scores are demonstrated on a subset of these simulated observations.

Contributions: I directly supervised this work, and co-authored the paper describing it.

[Full Paper](https://ieeexplore-ieee-org.kirtland.idm.oclc.org/abstract/document/9438185)


*The Dynamic Optical Telescope System: Collaborative Autonomous Sensing for Space Domain Awareness*. Justin Fletcher, Dave Archambeault, John Schmidt, Richard Peterson, Paul Sydney, Scott Hunt.
Journal of Defense Research and Engineering, Vol. 4, Issue 3, Pages 10-18. Defense Technical Information Center (2021).

Abstract: Space domain awareness is foundational to national defense. As great power competition and commercial space utilization increase the population and dynamism of resident space objects, space domain awareness systems must evolve to become more responsive to the space environment. This article describes the Dynamic Optical Telescope System (DOTS), an autonomous system comprising several heterogeneous optical telescopes that collaboratively and responsively observe the space environment. The system is described from several perspectives, including abstract architecture, mission-oriented design, system implementation, and mission performance. DOTS is the culmination of decades of multidisciplinary applied and basic research and development, and empirically demonstrates improved mission effectiveness through autonomy.

Full Paper: The contents of this paper are Controlled Unclassified Information. Please [contact me](mailto:jfletch@hawaii.edu) if you would like to request access.



*Inferring Space Object Orientation with Spectroscopy and Convolutional Networks*. Matthew Phelps, J Zachary Gazak, Thomas Swindle, Justin Fletcher, Ian McQuaid.
Advanced Maui Optical and Space Surveillance (AMOS) Technologies Conference 2021 (AMOS 2021) (2021).

Abstract: Accurate inference of a space object’s orientation is imperative for deriving its operational status and coordinating effective space traffic management at large. To formulate the framework necessary for solving the problem of orientation inference, we analyze several standard mathematical representations of rotation with an emphasis on continuity, uniqueness, and deep learning efficacy. On this basis, we are naturally led to the implementation of a lesser known but well-behaved 6D representation of rotation. For the input of our inference models, we employ a distance-invariant observational technique that has long been used to probe the furthest reaches of the universe at the smallest scales–spectroscopy. Facilitated by deep convolutional neural networks (CNN’s), we investigate the viability of using simulated raw, long slit spectroscopic images to infer the orientation of space objects in the nonresolved regime of large orbital radii. We present methods and results of training CNN’s on spectral images of several space objects with an aim to i) standardize the measures used in rotation analysis, ii) establish an upper bound on spectral-based performance, and iii) provide a simple-scenario baseline for the extension of future work in the application of spectroscopy to space domain awareness.

Contributions: I designed and initiated this project and directly supervised its execution.

A Note on Scholarly Rigor: AMOS is an archival conference and provides limited peer review (typically only two reviewers). It is, however, the premier conference for research related to space domain awareness; as such, papers published here can be impactful (e.g., influencing millions of dollars of defense spending) but should also be evaluated on the basis of thier content.

[Full Paper](https://amostech.com/TechnicalPapers/2021/Machine-Learning-for-SSA-Applications/Phelps.pdf)



*Semantic Segmentation of Low Earth Orbit Satellites using Convolutional Neural Networks*. Julia Yang, Jacob Lucas, Trent Kyono, Michael Abercrombie, Ian McQuaid, Justin Fletcher. 
Advanced Maui Optical and Space Surveillance (AMOS) Technologies Conference 2021 (AMOS 2021) (2021).

Abstract: Ground-based imaging of Low Earth Objects (LEO) is subject to perturbations by atmospheric turbulence, which makes it difficult to identify key features or components on the object of interest. Techniques for reconstructing images have been developed, but it is still up to a human to subjectively discern and identify truth features on a partially reconstructed image. In this paper, we present a neural network approach for semantic segmentation of ground-based images of LEO objects. We investigate the performance under various atmospheric turbulence strengths in terms of the Fried parameter (r0) and show the viability of this method.

Contributions: I designed and initiated this project and directly supervised its execution.

[Full Paper](https://amostech.com/TechnicalPapers/2021/Poster/Yang.pdf)


*lf-Supervised Auxiliary Task Learning for Estimating Satellite Orientation*. Klaus Okkelberg, Jacob Lucas, Trent Kyono, Michael Abercrombie, Matthew Phelps, Justin Fletcher.
Advanced Maui Optical and Space Surveillance (AMOS) Technologies Conference 2021 (AMOS 2021) (2021).

Abstract: Understanding the orientation or pose of a satellite is critical for space domain awareness. Recent advancements in direct pose estimation using convolutional neural networks (CNNs) have motivated us to examine a data-driven, end-to-end solution for estimating satellite pose. In this work, we use a CNN to directly estimate the pointing angle of a resolved LEO object. To improve the generalization of this task to varying objects, we perform classification as an auxiliary task for regularization. Both supervised and self-supervised learning methods are explored. We show on a large synthetic dataset, that multi-task self-supervision can improve the primary task of pointing angle estimation and improves generalization to held-out objects.

Contributions: I initiated this project and directly supervised its execution.

[Full Paper](https://amostech.com/TechnicalPapers/2021/Poster/Okkelberg.pdf)


*Discovering 3-D Structure of LEO Obects*. Jacob Lucas, Trent Kyono, Julia Yang, Justin Fletcher.
Advanced Maui Optical and Space Surveillance (AMOS) Technologies Conference 2021 (AMOS 2021) (2021).

Abstract: A 3-D object model provides invaluable information for space domain awareness. However, in practice, there are countless reasons why a 3-D object model may not exist or is unattainable. In this work, we aim to investigate the discoverability of 3-D object structure from passive observations of objects. Specifically, we aim to investigate the feasibility of using Neural Networks via Neural Radiance Fields for uncovering 3-D object models. Experimentally, we demonstrate feasibility on a simulated set of satellite images, where we can compare object structure to ground-truth.

Contributions: I designed and initiated this project and directly supervised its execution.

[Full Paper](https://amostech.com/TechnicalPapers/2021/Poster/Lucas.pdf)


*Toward deep-space object detection in persistent wide field of view camera arrays*. Garrett Fitzgerald, Zachary Funke, Alexander Cabello, Vijayan Asari, Justin Fletcher.
Advanced Maui Optical and Space Surveillance (AMOS) Technologies Conference 2021 (AMOS 2021) (2021).

Abstract: Persistent, static telescope arrays leverage a scalable imaging architecture to enable detection of dim deep-space objects while maintaining a wide field of view. The PANDORA (Persistent AND Optically Redundant Array) system, a 5× 9 array of commercial-off-the-shelf cameras, is an exemplar of this maturing sensing concept located at the Air Force Maui Optical and Supercomputing site. The PANDORA system is designed to capture 20◦× 120◦ wide field of view (WFOV) images of the night sky at a rate of two frames per minute, requiring advanced processing strategies to rapidly detect and track objects of interest. Wide area motion imagery (WAMI) object detection methods that extract scene object features are found to be effective in this WFOV space object detection and tracking application, and are used to demonstrate the exploitation capabilities of the PANDORA sensor system. In this work, we apply WAMI-inspired methods to the passive WFOV space object detection problem, with performance measured using a synthetic PANDORA dataset. We report the performance of three WAMI-inspired techniques for geosynchronous equatorial orbit (GEO) object detection, providing baseline GEO object detection measurements in PANDORA imagery.

Contributions: I initiated this project and advised the author throughout execution.

[Full Paper](https://amostech.com/TechnicalPapers/2021/Machine-Learning-for-SSA-Applications/Fitzgerald.pdf)

## Literature Review

*Reinforcment Learning for Optical System Control: A Literature Review*
Justin Fletcher.
[Full Paper](https://justinfletcher.github.io/_data/lit_review.pdf)
