---
title: "Spacetime Expression Cloning for Blendshapes"
type: journal
authors: ["Yeongho Seol", "J. P. Lewis", "Jaewoo Seo", "Byungkuk Choi", "Ken Anjyo", "Junyong Noh"]
conference: "SIGGRAPH"
journal: "ACM Transaction on Graphics"
thumb: "thumb.png"
teaser: "teaser.jpg"
---

## Abstract

The goal of a practical facial animation retargeting system is to reproduce the character of a source animation on a target face while providing room for additional creative control by the animator. This paper presents a novel direct method for facial animation retargeting. Our approach starts from the basic principle that the source and target movements should be similar. By interpreting movement as the derivative of position with time, and adding suitable boundary conditions, we formulate the retargeting problem as a Poisson equation. Specified (e.g. neutral) expressions at the beginning and end of the animation as well as any user specified constraints in the middle of the animation serve as boundary conditions. In addition, a modelspecific prior is constructed to represent the plausible expression space of the target face during retargeting. A Bayesian formulation is then employed to produce target animation that is consistent with the source movements while satisfying the prior constraints. We apply the proposed method to retarget various facial animations to arbitrary target faces. The resulting animations show the same temporal coherence and character of the source animations and exhibit smooth and controlled propagation of user edits across surrounding frames.

## Video
{% include youtube.html id="31LcS1aYius" %}
