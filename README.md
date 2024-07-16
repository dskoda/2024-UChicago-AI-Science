# Tutorials for the UChicago AI + Science Summer School 2024

## Contents

This repository contains the code for the tutorial on [Atomistic Adversarial Attacks](https://github.com/dskoda/Atomistic-Adversarial-Attacks) and [QUESTS: Quick Uncertainty and Entropy from STructural Similarity](https://github.com/dskoda/quests) presented to the [UChicago AI + Science Summer School 2024](https://datascience.uchicago.edu/events/ai-science-summer-school-2024/).
The notebooks are available in Google Colab at the following links:

- Atomistic Adversarial Attacks: <https://bit.ly/UChicago-AtomAttacks>
- QUESTS: <https://bit.ly/UChicago-Entropy>

The tutorials have some precomputed information in folder named [results](results) and datasets in the folders [gap20](gap20) and [rmd17](rmd17).
Only part of the datasets are available in this repository for brevity.

## References

### Papers

The references for the papers are:

- D. Schwalbe-Koda*, A. R. Tan*, and R. Gomez-Bombarelli.
Differentiable sampling of molecular geometries with uncertainty-based adversarial attacks.
*Nat. Commun.* **12**, 5104 (2021).
[Link](https://www.nature.com/articles/s41467-021-25342-8)

- D. Schwalbe-Koda et al.
Information theory unifies atomistic machine learning, uncertainty quantification, and materials thermodynamics.
arXiv:2404.12367 (2024).
[Link](https://doi.org/10.48550/arXiv.2404.12367)

### Datasets

The full references for the datasets are:

- **GAP-20**: P. Rowe, V. L. Deringer, P. Gasparotto, G. Csányi, and A. Michaelides.
"An accurate and transferable machine learning potential for carbon."
The Journal of Chemical Physics 153 (2020).
DOI: <https://doi.org/10.1063/5.0005084>.
Dataset: <https://www.repository.cam.ac.uk/items/ac362ef1-fa35-4bd4-8b56-2fde6d7b1d2c>
- **MD-17**: S. Chmiela, A. Tkatchenko, H. E. Sauceda, I. Poltavsky, K. T. Schütt, and K.-R. Müller
"Machine learning of accurate energy-conserving molecular force fields."
Science Advances 3 (2017).
DOI: <https://doi.org/10.1126/sciadv.1603015>.
- **rMD-17**: A. Christensen and O. A. von Lilienfeld.
"On the role of gradients for machine learning of molecular energies and forces."
Machine Learning: Science and Technology
DOI: <https://doi.org/10.1088/2632-2153/abba6f>
Dataset: <https://figshare.com/articles/dataset/Revised_MD17_dataset_rMD17_/12672038>


## License

This repository is made available under the [BSD-3 License](LICENSE), with the exception of the parts of the datasets:

- The rMD-17 dataset is distributed under the Public Domain.
- The GAP-20 dataset is distributed under the [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).
