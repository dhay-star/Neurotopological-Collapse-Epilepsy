Project Title: Comparative Neurotopology — Experimental Validation of the FBD Salazar Theory

Project Overview :

This project presents a computational implementation of the Physicobioneurodynamic (FBD) Theory, originally proposed by Arturo Salazar Chon, through a comparative analysis of EEG neurotopology in epileptic patients and a healthy subject.

Using EEG recordings from the CHB-MIT Scalp EEG Database, the study models how informational complexity and network geometry evolve before, during, and after epileptic seizures — offering experimental support for the collapse of complexity described in the FBD framework.

Theoretical Foundation — FBD Salazar Theory :

According to Salazar’s Physicobioneurodynamic (FBD) Theory, brain activity transitions cyclically through three key phases:

Isostasis (Homeostatic Balance): stable and coherent information flow in healthy conditions.
Collapse of Complexity: during pathological events (e.g., seizures), the neural network loses multiscale organization and becomes hypersynchronized.
Reorganization: gradual recovery of variability and fractal structure after the collapse.

This code models these transitions using topological, informational, and geometric metrics derived from EEG signals  serving as a practical validation of the FBD neurodynamic principles.

Objectives :

Quantify and visualize neural complexity collapse predicted by the FBD model.
Compare the geometric topological structure of healthy and epileptic EEG networks.
Track pre-ictal, ictal, and post-ictal dynamics through entropy and curvature.

Datasets :

Epileptic EEG: CHB-MIT Scalp EEG Database (PhysioNet)
Pediatric patients with drug-resistant epilepsy (Boston Children’s Hospital)
Healthy EEG: Baseline resting-state EEG (/s01.csv)
Dataset Source: https://physionet.org/content/chbmit/1.0.0/

Methods and Framework :
Concept	Implementation	Theoretical Link
Permutation Entropy	ant.perm_entropy()	Information dynamics / energy flow
Ricci Curvature (Ollivier, 2009)	networkx graph curvature	Geometric organization of neural topology
Persistent Homology (Ripser)	ripser + persim	Topological resilience and structural depth
Fractal & Complexity Metrics	Hjorth, Lempel-Ziv, Hurst	Multiscale self-organization

Key Findings :

Across all analyzed stages (from 3 days ,3 hours , 5 min  before to post-seizure), epileptic patients consistently exhibited higher topological and geometric complexity compared to the healthy subject.

However, within the FBD theoretical framework, this increased complexity represents structural instability and informational disorder, not functional enhancement.
The epileptic brain, deprived of medication and exhibiting hypersynchronization, manifests persistent chaotic complexity, confirming the collapse–reorganization dynamics of the FBD model.

Scientific Interpretation :

The results align with Arturo Salazar Chon’s proposal that:

“Consciousness and stability arise from the dynamic coupling between energy flow (entropy) and geometric organization (fractal topology).”

During seizures, the system experiences an informational collapse, where entropy and curvature indicate a loss of diversity and network rigidity  precisely as predicted by the Physicobioneurodynamic model.

Tools and Libraries :

Python 3.10

MNE — EEG preprocessing

NetworkX — Ricci curvature networks

Ripser / Persim — Topological Data Analysis (TDA)

Antropy — entropy and complexity metrics

Matplotlib / NumPy / SciPy — computation and visualization



Salazar Theory Researcher : Arturo Salazar Chon 
Code writer : Dhay Amer Kadhim

Kaggle Notebook: 
FBD Part One :https://www.kaggle.com/code/engdhay/fbd-part-one
FBD Part Two :https://www.kaggle.com/code/engdhay/fbd-part-two
