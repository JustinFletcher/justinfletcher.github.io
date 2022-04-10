---
layout: essay  
type: essay  
title: Statement of Purpose  
date: 2022-04-09  
labels:
  - PhD Portfolio
--- 

*This page presents my statement of purpose in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). It summarizes my professional interests in research, teaching, service, and/or product development.*


## Background and Research Interests

Are we alone in the cosmos? The question of life's abundance is among the most fundamental unanswered questions about the universe we inhabit and has been approached from many scientific and instrumental perspectives. Yet we are scarcely closer to answering that question today than when it was first asked. Life-bearing worlds, if they exist, continuously transmit messages advertising their existence; these heralds of other life on other worlds fall unheeded on our planet. Why? The study of biosignatures has given us the language to understand these messages. Encoded in the spectral crags and peaks caused by emission and absorption, this language renders life recognizable at any distance. So why don’t we listen? Because we cannot hear them.

The spectral messages that tell us of exoplanetary life are small eddies awash in a sea of noise. Select any of the 5,000 stars known to host exoplanets and view it in the night sky. As you watch, photons from both the star and its planets enter your pupils and stimulate receptors on your retinas. Nearly all of the photons will have travelled to you from the star, but an infinitesimal fraction will have come from it’s nearby companion and will carry with them information about the molecular composition of the atmosphere through which they were reflected. If you could finely sort them by their incident angle and bin them by their wavelength, given enough time, you would be able to determine if the planet possessed chemical evidence of life. Obviously, this is beyond the limits inherent to our form. We build instruments to extend the range of our perception, but we have not yet built an instrument with the angular resolution and contrast necessary to directly image exoplanets for spectral analysis. 

Traditional monolithic glass and steel telescope designs are infeasible when scaled to extremely large optical baselines (i.e., mirror diameters) as is required to achieve the angular resolution necessary for direct exoplanet imaging. Many emerging telescope designs are extremely scalable, but these designs also introduce optical subsystem control challenges which must be solved to compensate for aberrations induced by the design. These aberrations complicate image formation and limit effective resolution but may be corrected by responsive articulation of optical elements. Additionally, different articulation choices result in different optical transfer characteristics opening the way to responsive interferometric control and, by extension, sub-diffraction imaging.

My research interests involve the development of algorithms that solve these control problems and enable intelligent control of light in optical systems. While direct exoplanet detection and spectral analysis is the motivation for this work, a large enough telescope is not yet built for that objective. There are, however, many analogous imaging targets in orbit around the Earth. Artificial Earth satellites are much nearer than exoplanets but are also much smaller and can be found in a variety of sizes at a range of distances. Satellite imaging is useful as a proxy for exoplanet imaging but is also intrinsically valuable for space traffic management.

## Progress

I have completed my first publication on learned optical interferometry and image recovery. This work was accepted and presented at SPIE Defense and Commercial Sensing in April 2022. This initial paper demonstrated that it is possible to jointly design open-loop articulation control and recovery algorithms that achieve reconstruction quality exceeding that of an equivalent-size monolithic aperture telescope. This work lacked several sources of error and noise that would exist in a real system but validates the hypothesis that image recovery beyond the diffraction limit of a classical monolithic telescope is possible.


##  Goals

During the next six months, I will complete my ongoing work in open-loop MTF ensemble design and and learned image recovery algorithms. Near-term extensions to recent work will include higher fidelity noise modeling, atmospheric aberrations, and several experiments. A bench-level demonstration platform for this system should be available in the fall, and I will likely attempt to apply these techniques on-sky in the fall. 

In the following year, I hope to develop a framework that unifies optical interferometry (i.e., closed loop optical element control) and sequential decision making under uncertainty. This framework would enable the design of intelligent visuomotor agents, likely via deep reinforcement learning, to perform closed-loop optical interferometry. If successful, this approach may serve as a foundational technique in optical system design and photonics.

After my PhD, I will continue in my role leading the artificial intelligence and autonomy portfolio of the USSF Special Projects division analytics branch. If successful, this research may motivate USSF investment in large, distributed aperture telescopes, which I would be well-suited to lead.

