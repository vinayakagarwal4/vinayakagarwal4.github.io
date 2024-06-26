---
permalink: /
title: "Vinayak Agarwal's homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About Me
=====
I am a PhD candidate at MIT MechE and work with [Prof. Josh McDermott](https://web.mit.edu/jhm/www/) in MIT's [Laboratory for Computational Audition](https://mcdermottlab.mit.edu/). My research aims at understanding how physical generative processes assist humans and artificial agents in making rich inferences about the world using sound. More broadly, I am intersted in the physics underlying  natural and musical sound prediction and how humans are able to make rich inferences from the sounds they are.

In the summer of 2023, I worked with the audio presence team at Meta Reality Labs Research to help augment spatial audio rendering on smart glasses and develop models of online sound synthesis.

Before this, I graduated from IIT Bombay with a BTech & MTech in Mechanical Engineering with a focus on acoustics and automation. For my masters thesis, I worked with [Prof. Sripriya Ramamoorthy](https://sites.google.com/site/auditoryandacousticslab/home) on inverse acoustic characterization of periodic reticulated foam. During my undergrad, I worked with [Dr. Mitsuko Aramaki](http://kronland.fr/topics/mitsuko-aramaki/) and [Dr. Richard Kronland-Martinet](https://kronland.fr/) at Laboratoire of de mecanique et d'acoustique (LMA), CNRS, Marseille, France on the SoniMove project and with [Prof. Arne Eigenfeldt](http://www.sfu.ca/~eigenfel/arne/about.html) at Simon Fraser University on automatic song transcription.

I am also a semi-professional [Indian classical musician](https://www.youtube.com/watch?v=RX8kgRuJnr4) and [Mohan Veena](https://en.wikipedia.org/wiki/Mohan_veena) artist.

Here is my [CV](https://vinayak-agarwal.com/files/vinayak_cv.pdf) if you are interested to know more.

Current Research Projects
======

Sample-efficient learning of object representations from audio
-----
In this research program, we design computational frameworks based on intuitive physics that allow for sample-efficient online learning of object representations through sound. We have found that if we  accurately model the physical aspects of the generative process that human listeners might be sensitive to, we are able to learn peceptually-salient material encodings with only a handful of training examples. This aims at computationally explaining the human ability of few shot learning through audio

Synthesis and perception of Rigid-Body Contact sounds (Auditory intuitive physics)
-----
Instantaneous and sustained contact between rigid bodies produce characteristic sounds. Human Listeners often use these sounds to make rich inferences about the world around them. Through this project, we aim to understand how the governing physics of these object interactions lead to the sounds that we hear and how humans solve the inverse problem to infer the physics from these sounds. In particular, we focus on impacts, scrapes, rolls and their combinations.

in DAFx 2021, we presented novel state-of-the-art models for perceptually relevant synthesis of scraping and rolling sounds. We added non-linear physical constraints to physics inspired source-filter models to synthesize realistic sounds with perceptually relevant control knobs. We also performed psychophysics experiments to show that these models produced significatly more realistic sounds than the previous models in literature. Another set of experiments show that scraping trajectory information conveyed through the sounds from these models is significantly more similar to the information conveyed by real-world recordings of these sounds.

Currently, we are testing -
1. how human listeners are able to separate out and use different stages of the physical generative process from the contact sounds they hear. For example, we seek to understand how they solve the ill-posed problem of separating reverb of the environment from the sounds of impact from an object.
2. whether humans infer physical parameters from sound and use them to make predictions about the future of the auditory scene and the latent physical scene.
3. if sound-derived physical represntations of objects are shared across types of contact sounds

ThreeDWorld
------

[TDW](https://www.threedworld.org/) is a 3D virtual world simulation platform, utilizing state-of-the-art video game engine technology. We are integrating the sound synthesis models we developed for impacts, scrapes and rolls into TDW to transform it into the only virtual world simulation platform to have physics based synthesis of contact sounds. 

TDW provides researchers with:

1. A general, flexible design that does not impose constraints on the types of use-cases it can support, nor force any particular metaphor on the user.
2. Support for multiple modalities -- visual rendering with near-photoreal image quality, coupled with superior audio rendering fidelity.
3. A comprehensive, highly extensible and thoroughly documented command and control Python API.
4. Multiple paradigms for object interaction, capable of generating physically-realistic behavior.

Impact sound synthesis has already been released. Stay tuned for future updates with scraping and rolling synthesis.

Cross-modal perception of physics
------
It is hypothesized that humans use internalized models of physics as bridges to combine information from different sensory modalities. In this research project, we are evaluating how humans- 
1. infer physical parameters of a scene by combining information from audition and vision
2. combine cues from audition and vision using internalized physics-based world models
3. rely on cues from different modalities to infer different physical parameters

Perceptual representations of musical instrument timbre
------
Timbre is usually defined as the character or quality of a musical sound or voice as distinct from its pitch and intensity. Musical instrument timbre poses as an interesting recognition problem in human listeners as there is a possibility of some internalized generative structures like in speech. 

Most of the work on musical instrument timbre has either taken a signal feature based approach rooted in psychophysical experiments or a tried to use a source-filter approach that was not able to establish a strong perceptual relevance. We try to look for the possibility of internalized physical generative structures that humans might be using for the generalization of instrument identity across different excitation types, dynamic levels and f0s.
