---
title: HPCCS
summary: High Performance Collision Cross Section calculator for molecular ions using the Trajectory Method.
tags:
  - Software
  - Mass Spectrometry
  - Ion Mobility
date: '2024-01-01'

external_link: 'https://github.com/cepid-cces/hpccs'

image:
  caption: HPCCS software
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: GitHub
    url: 'https://github.com/cepid-cces/hpccs'
---

**HPCCS** (High Performance Collision Cross Section) is a fast and accurate software for
calculating **collision cross sections (CCS)** of molecular ions, used in ion mobility
spectrometry–mass spectrometry (IMS-MS) experiments.

## Features

- Based on the **Trajectory Method (TM)** — the gold standard for CCS calculation
- Parallelized with OpenMP for high performance
- User-friendly input/output
- Supports common molecular file formats

## Citation

Zanotto, L. et al. *High performance collision cross section calculation — HPCCS*.
**Journal of Computational Chemistry**, 2018.
[DOI: 10.1002/jcc.25199](https://doi.org/10.1002/jcc.25199)

## Download

```bash
git clone https://github.com/cepid-cces/hpccs.git
cd hpccs
make
```
