# Supporting material for the Master's thesis

**Evaluating the Effectiveness of Chain-of-Thought Explanations in Large Language Models: An Empirical Study of User Understanding, Trust, and Perceived Transparency**

This repository contains selected supporting material for the 2026 Master's thesis submitted to Blekinge Institute of Technology.

## Contents

- `analysis/computed_statistics.txt` — aggregate descriptive and inferential statistics reported in the study.
- `prompts.txt` — the standard and Chain-of-Thought generation prompts.
- `questions.txt` — the ten experimental questions.
- `survey_instrument.txt` — the blank survey instrument, without participant responses.
- `responses/README.md` — notes on the twenty complete generated-response files expected for this project.

## Study overview

The study used a quantitative within-participant design with 25 participants. Each participant evaluated standard and Chain-of-Thought-style responses to ten reasoning-related questions using six five-point Likert-scale items. Analyses included descriptive statistics, Wilcoxon signed-rank tests with Holm adjustment, effect sizes, Cronbach's alpha, and Spearman correlation.

## Privacy and data availability

Raw participant-level survey exports are intentionally not included. The consent text covered academic research use and did not provide for public release; combinations of timestamps and background responses could also create a re-identification risk. The blank survey instrument and aggregate statistics are provided instead. The thesis states that derived analysis data, analysis scripts, and generated response materials are available from the author on reasonable request, subject to the original consent.

## Reproducibility note

The aggregate statistics summary is included, but the participant-level `derived_data.csv` and executable analysis scripts were not among the files supplied for this upload. Therefore, this repository does not yet independently reproduce the reported statistics.

## Files not uploaded

The thesis PDF was supplied in this conversation but is not included in this initial upload. Add it as `thesis/Final_Thesis.pdf` through GitHub's web interface or Git on your computer. The Google Forms response-export PDF is excluded because it contains participant-level survey responses. The supplied ChatGPT session extracts are partial, out of order, and contain page scaffolding; they are not suitable as publication response files. The twenty complete response files (`standard_q01.txt`–`standard_q10.txt` and `cot_q01.txt`–`cot_q10.txt`) should be added when the complete original texts are available.

## Licence

No licence is specified. All rights are reserved unless the author adds a licence.