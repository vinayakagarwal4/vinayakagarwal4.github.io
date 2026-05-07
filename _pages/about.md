---
permalink: /
title: "Vinayak Agarwal"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a founding team member and Principal AI Engineer at [K-Dense](https://k-dense.ai), and a researcher at the intersection of artificial intelligence, neuroscience, and the biology of aging. I completed my PhD at [MIT School of Engineering](https://engineering.mit.edu/) in 2025, working with [Prof. Josh McDermott](https://web.mit.edu/jhm/www/) in the [Laboratory for Computational Audition](https://mcdermottlab.mit.edu/). K-Dense is backed by the Google AI Futures Fund and the Accel Atoms program.

---

K-Dense
======

K-Dense grew out of Biostate AI, which the founding team built with the goal of applying large-scale AI to the biology of aging and disease. The core belief is simple but ambitious: AI systems should be able to do science, not just assist with it.

The work I am most proud of from this chapter is a collaboration with [Prof. David Sinclair](https://sinclair.hms.harvard.edu/) at Harvard Medical School — one of the world's leading researchers on the biology of aging. Together, we produced what we believe is among the first life sciences papers conducted end-to-end with AI collaboration: from data curation and hypothesis generation through analysis, interpretation, and writing. The paper maps tissue-specific aging signatures across the human transcriptome at unprecedented scale, and was made possible by autonomous AI pipelines that would have taken a conventional research team years to execute. This project represents the clearest proof-of-concept I have for the vision driving all of my work at K-Dense.

Beyond that collaboration, I spend my time building the AI infrastructure that makes this kind of science possible: foundation models trained on large biological datasets, autonomous multi-agent systems for scientific analysis, and methods for extracting calibrated, interpretable knowledge from high-dimensional biological measurements. The goal is always the same: compress the timelines of biological discovery, and make the kind of science that usually takes decades take months.

---

Vision: AI for Science
======

We are at an inflection point. For most of human history, scientific progress has been bottlenecked by the pace at which individual researchers can read, hypothesize, experiment, and iterate. Today, AI systems are capable of doing much of this work autonomously, and at a scale no human team can match.

My vision is a future in which AI agents serve as genuine scientific collaborators: reading the literature, formulating hypotheses, designing analyses, interpreting results, and synthesizing findings into actionable knowledge. Not as a replacement for human scientists, but as a force multiplier that frees them to think at higher levels of abstraction.

The deeper principle is that good science and good AI are made of the same stuff: rigorous generative models, calibrated uncertainty, and a commitment to understanding mechanism rather than just predicting outcomes.

---

PhD Research (MIT School of Engineering, 2019-2025)
======

My doctoral research asked a deceptively simple question: how do humans reverse-engineer the world around them using the sounds they hear? Every sound carries a physical signature of the process that created it. A bouncing ball, a scraping pen, a struck glass: each encodes the geometry, material, surface, and motion of the objects involved. Somehow, the human auditory system solves this inverse problem effortlessly and in real time, perceiving rich physical structure that no microphone can directly measure. My PhD, situated at the intersection of AI, neuroscience, and cognitive science, was an attempt to understand how.

**Synthesis and Perception of Rigid-Body Contact Sounds**

The first strand of my research studied the physics of rigid-body contact sounds: impacts, scrapes, and rolls. I built differentiable physical synthesis models that generate these sounds from interpretable physical parameters, then used those models to run psychophysical experiments probing what listeners can and cannot recover from sound alone. A key contribution was a source-filter model for scraping and rolling sounds that enforces non-linear mechanical constraints, allows for location-dependent material variation, and was validated in perceptual experiments showing that listeners extract physical information from the synthesized sounds at the same fidelity as from real recordings. [DAFx, 2021]

**Sample-Efficient Learning of Auditory Object Representations**

The second strand asked a learning question: given that humans can identify a material from just a handful of impact sounds, what computational structure makes this possible? I designed frameworks grounded in intuitive physics that learn perceptually salient object representations from audio with minimal supervision. The key insight is that accurately modeling the physical generative process constrains the hypothesis space enough that the auditory system can generalize from very few examples. This offers a computational account of few-shot physical inference through sound, and suggests that physical inductive biases are essential for building machines that learn the way humans do.

**Differentiable Physical Synthesis as a General Framework**

Across both threads, a unifying method emerged: differentiable physical synthesis, in which parameterized generative models grounded in physics are fit to observed data via gradient descent. Rather than learning purely statistical representations, these models invert the physical process to recover interpretable parameters: material stiffness, geometry, surface roughness. Models built this way generalize to new objects, require less data, and produce predictions that connect to physical intuition. I see this as a general blueprint for building AI systems that understand the world, not merely predict it.

---

Before MIT, I earned a BTech and MTech in Mechanical Engineering from **IIT Bombay**, with a focus on acoustics and automation. I worked with Prof. Sripriya Ramamoorthy on inverse acoustic characterization of periodic reticulated foam, and as an undergrad I worked at CNRS Marseille and Simon Fraser University on sound synthesis and music transcription.

I am also a semi-professional [Indian classical musician](https://www.youtube.com/watch?v=RX8kgRuJnr4) and [Mohan Veena](https://en.wikipedia.org/wiki/Mohan_veena) artist.

[[Google Scholar](https://scholar.google.com/citations?user=NTuU8YIAAAAJ)] [[CV](/files/vinayak_cv.pdf)] [[GitHub](https://github.com/vinayakagarwal4)] [[LinkedIn](https://linkedin.com/in/vinayak-agarwal-4b8238a0/)]
