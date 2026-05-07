---
permalink: /
title: "Vinayak Agarwal"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Principal AI Engineer at [K-Dense](https://k-dense.ai), where I build AI systems that accelerate biological research at scale. I completed my PhD at [MIT School of Engineering](https://engineering.mit.edu/) in 2025, working with [Prof. Josh McDermott](https://web.mit.edu/jhm/www/) in the [Laboratory for Computational Audition](https://mcdermottlab.mit.edu/). K-Dense is backed by the Google AI Futures Fund and the Accel Atoms program.

My work sits at the intersection of AI and science: I build systems that compress months of scientific discovery into days, and I study the physical and biological generative processes that underlie how both minds and organisms work.

---

Vision: AI for Science
======

We are at an inflection point. For most of human history, scientific progress has been bottlenecked by the pace at which individual researchers can read, hypothesize, experiment, and iterate. Today, AI systems are capable of doing much of this work autonomously, and at a scale no human team can match.

My vision is a future in which AI agents serve as genuine scientific collaborators: reading the literature, formulating hypotheses, designing analyses, running experiments computationally, and synthesizing results into actionable knowledge. Not as a replacement for human scientists, but as a force multiplier that frees them to think at higher levels of abstraction.

At K-Dense, I am building toward this vision in aging biology. We have constructed AI systems that autonomously analyze transcriptomic datasets, discover tissue-specific aging signatures, and generate testable hypotheses about longevity interventions. The same framework is generalizable: any biological question with sufficient data is now approachable at a pace that was impossible five years ago.

The deeper principle is that good science and good AI are made of the same stuff: rigorous generative models, calibrated uncertainty, and a commitment to understanding mechanism rather than just predicting outcomes.

---

Current Work (K-Dense)
======

**Transcriptomic Aging Clocks**
I built an ensemble aging clock trained on 57,584 samples across 28 tissues (ages 1-114 years), achieving R2 = 0.854 and MAE = 4.26 years with calibrated uncertainty intervals. The model operates as a mixture-of-experts system, allowing it to learn both universal and tissue-specific aging programs simultaneously. Stage-specific aging markers we have discovered include CDKN2A/p16, AMPD3, MIR29B2CHG, and SEPTIN3.

**GeneJepa**
A predictive world model of the transcriptome. GeneJepa learns representations of gene expression states and models how perturbations propagate through the transcriptome, enabling principled prediction of downstream regulatory effects. [bioRxiv, 2025]

**Revive-Flow**
A foundation model for blood DNA methylation aging. Revive-Flow learns the epigenomic landscape of aging from large-scale methylation datasets and produces calibrated biological age estimates. [bioRxiv, 2025]

**K-Dense Analyst**
An autonomous AI system for end-to-end scientific analysis. K-Dense Analyst orchestrates multi-agent pipelines that take a biological question from raw data to publication-ready results, compressing months of research into days. [arXiv, 2025]

---

PhD Research (MIT School of Engineering, 2019-2025)
======

My doctoral work studied **auditory intuitive physics**: how humans use sound to make rich inferences about the physical world. Everyday sounds carry signatures of the physical processes that produced them. A scraping pen, a bouncing ball, a struck wine glass: each sound encodes the material, geometry, surface texture, and motion of the objects involved. My research asked how the human auditory system solves this inverse problem, and whether we can build computational models that do the same.

**Synthesis and Perception of Rigid-Body Contact Sounds**

Instantaneous and sustained contact between rigid bodies produces characteristic sounds. Human listeners use these sounds to make rich inferences about their surroundings. Through this project, I studied how the governing physics of object interactions lead to the sounds we hear, and how humans solve the inverse problem to infer physical causes from those sounds. I focused on impacts, scrapes, and rolls.

A central contribution was a novel source-filter model for realistic synthesis of scraping and rolling sounds, with physically and perceptually relevant parameters constrained by mechanics. Key features include non-linearities to constrain contact force, naturalistic normal force variation for different motions, and a method for morphing impulse responses within a material to achieve location-dependence. Perceptual experiments confirmed the model synthesizes realistic sounds while conveying physical information comparable to real recordings. [DAFx, 2021]

**Sample-Efficient Learning of Auditory Object Representations**

Human listeners can identify the material, size, and shape of an object from just a handful of impact sounds. How? In this research program, I designed computational frameworks grounded in intuitive physics that allow for sample-efficient online learning of object representations from audio.

The key insight is that if we accurately model the physical aspects of the generative process that human listeners are sensitive to, we can learn perceptually salient material encodings with only a handful of training examples. This work offers a computational account of the human ability to do few-shot learning through sound, and builds toward machine perception systems that can acquire physical knowledge from audio with minimal supervision.

**Differentiable Physical Synthesis for Inverse Problems in Acoustics**

A through-line across my PhD work was the use of differentiable physical synthesis models: parameterized generative models of sound grounded in physics that can be fit to observed data via gradient descent. Rather than learning purely statistical representations, these models invert the physical process to recover interpretable parameters: material stiffness, object geometry, surface roughness.

This approach gives models that generalize better across new objects and materials, produce interpretable predictions that connect to physical intuition, and learn efficiently from limited data because the physics constrains the hypothesis space.

---

Before MIT, I earned a BTech and MTech in Mechanical Engineering from **IIT Bombay**, with a focus on acoustics and automation. I worked with Prof. Sripriya Ramamoorthy on inverse acoustic characterization of periodic reticulated foam. As an undergrad, I worked at CNRS Marseille on the SoniMove project (with Dr. Mitsuko Aramaki and Dr. Richard Kronland-Martinet) and at Simon Fraser University on automatic song transcription (with Prof. Arne Eigenfeldt).

I am also a semi-professional [Indian classical musician](https://www.youtube.com/watch?v=RX8kgRuJnr4) and [Mohan Veena](https://en.wikipedia.org/wiki/Mohan_veena) artist.

[[Google Scholar](https://scholar.google.com/citations?user=NTuU8YIAAAAJ)] [[CV](/files/vinayak_cv.pdf)] [[GitHub](https://github.com/vinayakagarwal4)] [[LinkedIn](https://linkedin.com/in/vinayak-agarwal-4b8238a0/)]
