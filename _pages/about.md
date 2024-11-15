---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a postdoc in the [Hearing Systems Research Section at DTU](https://www.healthtech.dtu.dk/research/research-sections/section-hearing-systems) developing machine learning models of human hearing. I am interested in how our ears and environment shape auditory perception and my research focuses on neural coding, hearing loss, and audio enhancement via deep learning. Before moving to Denmark, I completed my PhD in Brain and Cognitive Sciences at MIT, working with Josh McDermott in the [Laboratory for Computational Audition](http://mcdermottlab.mit.edu). I first became interested in the hearing sciences though undergraduate research positions in the field of marine mammal acoustics at the [Woods Hole Oceanographic Institution](https://www.whoi.edu/what-we-do/educate/undergraduate-programs/summer-student-fellowship/) and the [Scripps Institution of Oceanography](https://scripps.ucsd.edu/mpl/mpl-summer-internship-program). I completed my undergraduate studies in biology and chemistry at the University of Chicago, where I was also a research assistant in the Epilepsy Lab.


Research
======

Hearing loss and audio enhancement via deep learning
------
While extensive modeling efforts in the past few decades have resulted in good computational descriptions of peripheral auditory processing (capable of predicting auditory nerve responses to arbitrary stimuli), much less is known about how the rest of the auditory system uses that input to create our sense of hearing. Humans with normal hearing have the remarkable ability to recognize and make sense of sounds in noisy environments with multiple competing sources. However, this ability is fragile and is greatly compromised in listeners with hearing impairment or cochlear implants, often leading to frustration and social isolation. Current assistive devices largely fail to aid impaired listeners in noisy environments, and the development of more effective devices is currently limited by an incomplete understanding of how changes in peripheral processing believed to accompany hearing loss lead to changes in complex auditory behavior. My research combines deep learning with detailed models of cochlear signal processing to address this need. I aim to build computational models that link specific aspects of (altered) peripheral processing to real-world auditory behavior and then leverage these models to develop more effective assistive hearing technology.

Perceptual role of auditory nerve phase locking
------
The auditory nerve encodes sound with spike-timing that is phase locked to the fine-grained temporal structure of sound. The precision of this coding substantially exceeds that of any other sensory modality, but its role in hearing remains controversial because physiological mechanisms for extracting information from the spike timing have proven elusive. We are using deep artificial neural networks in the spirit of ideal observer analysis to investigate the perceptual role of auditory nerve phase locking. We train networks to perform everyday hearing tasks (such as recognizing and localizing speech, voices, and environmental sounds) from simulated cochlear input. We then ask whether phase locking in the input representation is necessary to account for human behavior. This line of work may help clarify conditions in which auditory prostheses that fail to restore high-fidelity temporal coding (e.g., contemporary cochlear implants) should and should not be expected to restore near-normal hearing.

Pitch perception
------
Pitch perception is arguably the most studied aspect of human hearing. Yet despite a wealth of human data, the underlying computations and constraints that determine pitch perception remain debated. We developed a new pitch model by optimizing deep artificial neural networks to estimate fundamental frequency from biologically faithful cochlear representations of natural sounds. Despite never being fit to human data in any way, the resulting model closely replicated many characteristics of human pitch perception. To probe the origins of these characteristics, we then optimized networks given altered cochleae or sound statistics. Human-like behavior emerged only when cochleae had high temporal fidelity and when models were optimized for naturalistic sounds. The results suggest pitch perception is critically shaped by the constraints of natural environments in addition to those of the cochlea, illustrating the  use of artificial neural networks to reveal underpinnings of behavior.
