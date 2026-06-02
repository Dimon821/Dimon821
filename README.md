# Simon Wagener

Molecular Life Sciences student at Radboud University specializing in computational analysis, structural bioinformatics, digital image processing, and data science. Main focuses involve leveraging machine learning, computer vision, and mathematical optimization frameworks to interpret complex biomolecular, structural, and medical data.

### About Me

* Currently studying Molecular Life Sciences at Radboud University in Nijmegen, Netherlands.
* Focused on bridging data science with life science workflows, converting complex raw experimental data into biological insights.
* Skilled in engineering automated data processing pipelines for structural prediction metrics, medical imagery, and high-throughput biochemistry instrumentation.

### Tech Stack and Life Science Toolbelt

| Category | Tools and Technologies |
| :--- | :--- |
| Programming | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-ED6B21?style=flat-square&logo=mathworks&logoColor=white) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white) |
| Hardware and Prototyping | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) |
| Data Science, ML & Bio | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=black) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) **YASARA** |

### Featured Interdisciplinary Projects

#### [YASARA AlphaFold Viewer](https://github.com/Dimon821/yasara-alpha-viewer)

An interactive desktop analysis dashboard that bridges AlphaFold structural prediction metrics with 3D molecular viewports by binding a custom Matplotlib control interface directly to YASARA via Python sockets.

* Engineered a dual-panel GUI to display 2D Predicted Aligned Error (PAE) matrices and 1D pLDDT confidence profiles simultaneously.
* Developed an interactive, dynamic PAE structure mapping engine where clicking anywhere on the 2D matrix map automatically re-colors the 3D YASARA viewport based on alignment errors relative to the selected focus residue.
* Implemented a native fallback loading engine to parse sequence-specific confidence intervals directly from CIF coordinate B-factor arrays when standard JSON metrics are absent, alongside a Tkinter-driven workspace swapping system.

#### [Bacterial respiratory pathogens share predicted MHC-II epitopes](https://github.com/Dimon821/Bacterial-pathogens-share-predicted-M MHC-II-epitopes)

Developed a high-throughput computational pipeline during my Bachelor's internship aimed at identifying shared T-cell epitopes across multiple respiratory bacterial pathogens, including *Bordetella pertussis*, *Haemophilus influenzae*, *Streptococcus pneumoniae*, and *Streptococcus pyogenes*. 

* Leveraged NetMHCIIpan-4.0 in conjunction with custom proteomics lookup tables to systematically map the entire peptide repertoire of these species.
* Built a robust data processing framework integrating peptide n-mer extraction, MHC-II binding affinity predictions, and phylogenetic distribution analysis to pinpoint cross-reactive vaccine targets, bridging genomic data with translational immunology.

#### [Retinal Blood Vessel Segmentation](https://github.com/Dimon821/image-analysis-of-retinal-blood-vessels)

An automated computer vision and image processing pipeline designed to map complex microvascular structures from retinal fundus photographs utilizing the DRIVE dataset.

* Implemented multi-stage preprocessing including green channel separation, CLAHE contrast stretching, illumination homogenization, and morphological cleanups to isolate high-contrast vascular morphology.
* Configured a 15-dimensional Bayesian Optimization framework using `skopt.gp_minimize` to mathematically maximize segmentation evaluation metrics like AUC ROC and Dice similarity coefficients without manual parameter tuning.

#### [Data Science Project: Cyclotron Mass Spectrometry](https://github.com/Dimon821/Data-Science-Project-Cyclotron-Mass-Spec)

A dedicated data science environment optimized for cleaning, decoding, and rendering spectral data profiles from deep molecular laboratory readouts. Leveraged the mathematical ecosystem of Python to handle mass spectrometry variables and visualize distributions for analytical biochemistry research.

### Connect with Me

Open to discussing computational biology, bioinformatics, computer vision pipelines, or collaborative scientific software developments.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Simon_Wagener-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-wagener-619938212/)
[![Academic Email](https://img.shields.io/badge/Academic_Email-simon.wagener@ru.nl-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:simon.wagener@ru.nl)
[![Private Email](https://img.shields.io/badge/Private_Email-swagener18@gmail.com-004C97?style=for-the-badge&logo=minutemailer&logoColor=white)](mailto:swagener18@gmail.com)
