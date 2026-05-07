---
title: "MetaMuse: A Multi-Agent AI System for Biomedical Metadata Curation and Harmonization"
collection: publications
date: 2026-04-15
venue: 'bioRxiv'
paperurl: 'https://doi.org/10.64898/2026.04.12.718044'
citation: 'Mittal, E., Litman, E., Myers, T., Agarwal, V., Gopinath, A., & Kassis, T. (2026). MetaMuse: A Multi-Agent AI System for Biomedical Metadata Curation and Harmonization. bioRxiv. https://doi.org/10.64898/2026.04.12.718044'
---

[Download paper here](https://doi.org/10.64898/2026.04.12.718044)

MetaMuse is a three-stage multi-agent AI pipeline for biomedical metadata curation and harmonization, targeting GEO datasets. CuratorAgents (Gemini-2.5) extract metadata candidates, an ArbitratorAgent enforces cross-field consistency, and a NormalizerAgent (SapBERT and FAISS) maps fields to standard ontology IDs (MONDO, UBERON, ChEMBL, NCBI Taxonomy, HANCESTRO, HSAPDV, PATO, CLO). The system achieves greater than 95% curation accuracy on a gold-standard benchmark of 100 samples, validated on 400 samples total. The pipeline is conservative by design, preferring false negatives over hallucinations.
