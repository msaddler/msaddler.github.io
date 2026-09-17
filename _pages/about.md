---
permalink: /
# title: "About me"
# excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a postdoc in the [Hearing Systems Research Section at DTU](https://www.healthtech.dtu.dk/research/research-sections/section-hearing-systems) developing machine learning models of human hearing. I am interested in how our ears and environment shape auditory perception and my research focuses on neural coding, hearing loss, and audio enhancement via deep learning. Before moving to Denmark, I earned my PhD from MIT's Department of Brain and Cognitive Sciences, working with Josh McDermott in the [Laboratory for Computational Audition](http://mcdermottlab.mit.edu). I first became interested in the hearing sciences through undergraduate research positions in the field of whale acoustics at the [Woods Hole Oceanographic Institution](https://www.whoi.edu/what-we-do/educate/undergraduate-programs/summer-student-fellowship/) and the [Scripps Institution of Oceanography](https://scripps.ucsd.edu/mpl/mpl-summer-internship-program). I completed my undergraduate studies in biology and chemistry at the University of Chicago.






Research
======

Computational models of healthy and impaired hearing
------
While extensive modeling efforts in the past few decades have resulted in good computational descriptions of the ear's signal processing, much less is known about how the rest of the auditory system uses that peripheral input to create our sense of hearing. Humans with normal hearing are remarkably adept at localizing and recognizing sounds in noisy environments with multiple competing sources. However, these abilities are fragile and greatly compromised in listeners with hearing impairment or cochlear implants, often leading to frustration and social isolation. Current assistive devices largely fail to aid impaired listeners in noisy environments, and the development of more effective devices is limited by our incomplete understanding of how the peripheral effects of hearing loss translate to perceptual consequences. My research combines deep learning with detailed simulations of cochlear signal processing to address this need. I build computational models that generate real-world auditory behavior from realistic peripheral input and use these models to better understand, diagnose, and treat hearing loss.


Temporal coding in hearing
------
The ear exhibits incredibly precise spike timing, but the role of this timing in perception has been unclear. Knowing this role is important for understanding hearing loss and auditory prosthetics. We tackled this problem by optimizing artificial neural networks to perform auditory tasks using input from simulated auditory nerve fibers, and testing whether high-fidelity spike timing (“phase locking”) was necessary to match human behavior. The results show that models require some degree of phase locking to exhibit human-like behavior, but that the extent needed depends on the domain (sound localization, voice recognition, or word recognition). This variation across task domains was largely explained by the temporal fidelity needed to achieve good task performance in real-world conditions (hearing in noise), indicating that different domains incorporate temporal coding as needed for what they have to do. These findings offer a normative explanation for the brain’s use of a specific neural coding cue and provide insight into the cues that cochlear implants must preserve to restore normal hearing.



Pitch perception
------
Pitch perception is arguably the most studied aspect of human hearing. Yet despite a wealth of human data, the underlying computations and constraints that determine pitch perception remain debated. We developed a new pitch model by optimizing deep artificial neural networks to estimate fundamental frequency from biologically faithful cochlear representations of natural sounds. Despite never being fit to human data in any way, the resulting model closely replicated many characteristics of human pitch perception. To probe the origins of these characteristics, we then optimized networks given altered cochleae or sound statistics. Human-like behavior emerged only when cochleae had high temporal fidelity and when models were optimized for naturalistic sounds. The results suggest pitch perception is critically shaped by the constraints of natural environments in addition to those of the cochlea, illustrating the  use of artificial neural networks to reveal underpinnings of behavior.
