# A Generative Model for Pokémon Unown

## Overview
This project explores a **generative modeling approach** for Pokémon *Unown* characters, a unique Pokémon species whose forms correspond to alphabet-like symbols. Due to their structured yet discrete visual variations, Unown characters provide a compact and interpretable testbed for studying **representation learning and generative models**.

The goal of this project is to learn a latent representation that captures the underlying structure of Unown images and enables meaningful generation.

---

## Motivation
Unlike natural images with high visual diversity, Unown characters:
- Have low-resolution, structured shapes
- Exhibit clear intra-class variation
- Possess semantic structure tied to symbolic forms

These properties make them ideal for analyzing how generative models encode shape, structure, and variation in a controlled setting.

---

## Methodology
- Image preprocessing and normalization
- Latent-variable generative modeling
- Training via variational or likelihood-based objectives
- Sampling from the learned latent space to generate new Unown-like images

The notebook emphasizes **model behavior and qualitative analysis** rather than pure benchmark performance.

---

## Experiments and Analysis
- Visualization of reconstructed Unown characters
- Sampling from the latent space
- Inspection of how latent variables correspond to visual attributes
- Discussion of model strengths and limitations

