# Biohub cell tracking: reproduction and evaluation

## Problem and contribution

Track cells across 3D microscopy frames while preserving valid temporal links and division structure. My work focused on reproducing public baselines, comparing inference variants, inspecting submission graphs and keeping versioned experiment records.

## Work documented in the local experiment log

- Compared probability-mean, logit-mean and median heatmap fusion.
- Tested model-member ablations and different test-time augmentation views.
- Audited submission schemas, finite values, coordinate bounds, forward-time edges, endpoint integrity, duplicate edges and graph degree constraints.
- Preserved unsuccessful experiments to distinguish a plausible model change from an improvement supported by evaluation.
- Recorded a separate reproduction of a public dual-model pipeline and its submission reference.

## Evaluation boundaries

Public leaderboard scores do not measure generalization to all embryos. Local validation should keep embryos and fields of view separated; random neighboring-frame splits can leak information. A reproduced public pipeline is credited as reproduction, not an original model architecture.

This case study contains no competition data, model weights, copied third-party notebooks or hidden labels. Scores and current competition results should be checked against the submission history on my [Kaggle profile](https://www.kaggle.com/cluckinvv). It is a documentation case study, not a redistributable training package.
