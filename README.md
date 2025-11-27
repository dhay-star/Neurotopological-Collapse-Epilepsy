Project Title:
Comparative Neurotopology Experimental Validation of Neural Complexity Collapse in Epilepsy

Project Overview:
This project presents a computational study demonstrating that epileptic seizures lead to a collapse of neural complexity, not just abnormal electrical activity. EEG recordings from the CHB-MIT Scalp EEG Database were analyzed across pre-ictal, ictal, and post-ictal periods, spanning 5 days, 3 hours, and 5 minutes before and after seizures.

Parts 1–3 – Empirical Validation (Methodology by Arturo Salazar, Code by Dhay Amer Kadhim):

Structural Complexity (S): Derived from Ricci curvature and curvature variance to quantify network geometry integrity.

Informational Differentiation (I): Permutation entropy captures the predictability and diversity of neural signals.

Coherence (C): Correlation structure and H1 persistence measure temporal coordination and topological resilience.

Summary: These metrics were computed per patient and visualized over time. Results consistently show that during seizures, epileptic brains exhibit high variability in S, I, C, indicating structural instability and informational disorder, confirming collapse of neural complexity.

ΔΦ Operator (Integration of S/I/C Metrics):

ΔS(x) = S(x) − S_baseline

ΔI(x) = I(x) − I_baseline

ΔC(x) = C(x) − C_baseline

ΔΦ(x) = 0.40 ⋅ |ΔS(x)| + 0.35 ⋅ |ΔI(x)| + 0.25 ⋅ |ΔC(x)|

Interpretation: ΔΦ quantifies deviation from baseline, classifying brain states into:

Isostasis: ΔΦ < 0.15

Allostasis: 0.15 ≤ ΔΦ < 0.35

High-Allostasis: 0.35 ≤ ΔΦ < 0.40

Collapse: ΔΦ ≥ 0.40

Collapse segments are detected when ΔΦ ≥ 0.40 for ≥2 consecutive windows, robustly identifying critical breakdowns.

Part 4 – FBD Neurodynamic Theory (Theory by Kaboth, Wende, Krüger; Application by Dhay Amer Kadhim):
This framework models brain dynamics along the three DLHR axes (S, I, C), integrating structural, informational, and coherence dimensions.

Core Idea: ΔΦ measures weighted deviations along S/I/C axes from baseline to detect functional breakdowns.

Application: EEG datasets are evaluated under this theory to confirm the collapse–reorganization dynamics predicted by FBD.

Key Findings:

Across 5-day, 3-hour, and 5-minute windows, epileptic patients consistently showed persistent high variability in S, I, C, reflecting network instability.

ΔΦ analysis identifies critical collapse periods, confirming theoretical thresholds.

Healthy EEG exhibits stable S, I, C, and ΔΦ remains mostly below 0.15 (Isostasis).

Tools and Libraries:

Python 3.10

MNE — EEG preprocessing

NetworkX — Ricci curvature networks

Ripser / Persim — Topological Data Analysis (TDA)

Antropy — Entropy and complexity metrics

Matplotlib / NumPy / SciPy — Computation and visualization

Credits:

Methodology / Parts 1–3: Arturo Salazar (research)

Code Implementation / Analysis: Dhay Amer Kadhim

FBD Theory / Part 4: Pasquale Kaboth, Marcel Theodor Wende, Marcel Krüger

Application of Theory: Dhay Amer Kadhim


Kaggle Notebook: 

 Part One : [https://www.kaggle.com/code/engdhay/fbd-part-one](https://www.kaggle.com/code/engdhay/eeg-part-one)
 Part Two : [https://www.kaggle.com/code/engdhay/fbd-part-two](https://www.kaggle.com/code/engdhay/eeg-part-two)
 part Three: [https://www.kaggle.com/code/engdhay/eeg-part-three](https://www.kaggle.com/code/engdhay/eeg-part-three)
 part four: [https://www.kaggle.com/code/engdhay/eeg-part-four](https://www.kaggle.com/code/engdhay/eeg-part-four)

