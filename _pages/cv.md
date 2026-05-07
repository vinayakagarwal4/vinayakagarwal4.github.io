---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D., Brain and Cognitive Sciences**, MIT, 2025
  * Advisor: Prof. Josh McDermott, Laboratory for Computational Audition
  * Thesis: *Synthesis and perception of sounds from physical interactions reveals auditory intuitive physics*
* **B.Tech. and M.Tech., Mechanical Engineering**, IIT Bombay, 2019
  * Focus: Acoustics and automation
  * Masters thesis: Inverse acoustic characterization of periodic reticulated foam (with Prof. Sripriya Ramamoorthy)

Work Experience
======
* **Principal AI Engineer**, K-Dense Inc., 2024 - Present
  * Lead AI research on transcriptomic aging, foundation models for biology, and autonomous scientific analysis
  * Built ensemble transcriptomic aging clock: R2 = 0.854, MAE = 4.26 years, trained on 57,584 samples across 28 tissues
  * Co-developed GeneJepa (predictive world model of the transcriptome) and Revive-Flow (foundation model for blood DNA methylation aging)
  * Built K-Dense Analyst: autonomous AI system compressing months of scientific analysis into weeks
  * K-Dense is backed by Google AI Futures Fund and Accel Atoms program

* **Research Intern**, Meta Reality Labs Research, Summer 2023
  * Augmented spatial audio rendering on smart glasses
  * Developed models for online sound synthesis

* **Graduate Research Assistant**, MIT Laboratory for Computational Audition, 2019 - 2025
  * Studied auditory intuitive physics: rigid-body impact, scraping, and rolling sounds
  * Built differentiable physical synthesis models; ran psychophysical experiments
  * Advisors: Prof. Josh McDermott and Prof. Josh Traer

* **Research Intern**, CNRS Laboratoire de Mecanique et d'Acoustique, Marseille, France
  * SoniMove project: perceptual studies and sound synthesis (with Dr. Mitsuko Aramaki and Dr. Richard Kronland-Martinet)

* **Research Intern**, Simon Fraser University
  * Automatic song transcription (with Prof. Arne Eigenfeldt)

Skills
======
* **Machine learning:** PyTorch, JAX, transformers, diffusion models, probabilistic modeling
* **Computational biology:** transcriptomics, epigenomics, aging clocks, RNA-seq pipelines
* **Scientific computing:** Python, NumPy, SciPy, Pandas, scikit-learn
* **Audio and acoustics:** physical synthesis models, psychoacoustics, signal processing
* **Autonomous AI systems:** multi-agent pipelines, AI-driven research workflows

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Selected Awards and Affiliations
======
* Google AI Futures Fund (K-Dense), 2024-2025
* Accel Atoms Program (K-Dense), 2025
* MIT Graduate Research Fellowship, 2019-2025
