# Contextual Deference

Mechanistic interpretability analysis of how stated intent overrides safety activations in Gemma 2 9B.

## Key Finding
Stated intent ("I need a distraction") creates a vector that is the geometric inverse of the risk/refusal direction (cosine similarity = −0.93).

## Contents
- `contextual_deference.ipynb` — Full analysis notebook
- `contextual_deference_trajectory.png` — Layer-wise trajectory visualization

## Author
Ava Chen | MATS 10.0 Application | January 2026
