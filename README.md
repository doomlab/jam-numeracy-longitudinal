## Counting on Memory: How Expertise Shapes Our Numerical Judgments of Associations

This repository contains the materials, code, and data for the paper:

Counting on Memory: How Expertise Shapes Our Numerical Judgments of Associations

📄 Overview

This project investigates how people estimate the associative strength between word pairs and how repeated interaction with stimuli (expertise) shapes bias and sensitivity in these judgments.
	•	Bias refers to systematic overestimation of association probabilities.
	•	Sensitivity reflects the ability to discriminate between high- and low-strength associations.
	•	Analyses compare participant-generated norms against established free association databases (Nelson et al., 2004; De Deyne et al., 2019).

📂 Repository Structure

├── 0_IRB/             # Institutional Review Board (IRB) materials
├── 1_Materials/       # Study materials, instructions, and survey content
├── 2_Data/            # Raw and processed data files
├── 3_Manuscript/      # R Markdown manuscript, LaTeX, and output files
├── .gitattributes     # Git configuration file
└── README.md          # Project overview (this file)

📊 Data
	•	Norming dataset: Participant free association responses collected across five sessions.
	•	Reference databases:
	•	[@Nelson2004] Free Association Norms
	•	[@dedeyne2019] Small World of Words (SWOW) norms

🔧 Reproducibility

The analyses were conducted in R with the following key packages:
	•	tidyr, dplyr (data wrangling & visualization)
	•	nlme (linear mixed-effects models)
	•	papaja (manuscript formatting in APA style)
	•	patchwork (figure composition)
  •	rio (file opener)


✒️ Citation

If you use this code or data, please cite:

Buchanan, E.M. (2025). Counting on Memory: How Expertise Shapes Our Numerical Judgments of Associations. Manuscript submitted for publication.
