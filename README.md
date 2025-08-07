# The Irreducible Intent Model: Code and Data

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the official code, data, and analysis notebooks for the paper: **"Reclaiming Purpose in Science: Divine Teleology and the Irreducible Intent Model"**.

The Irreducible Intent Model (IIM) is a proposal for a new scientific paradigm grounded in the theological axiom based from the Holy Scriptures of the Bible, that reality is a projection of Jehovah God's Will. This repository provides the necessary materials to reproduce the key findings presented in the paper, including the analysis of astrophysical and genomic data.

## Repository Structure

The project is organized into folders corresponding to the four primary hypotheses tested in the paper:

* **/data/**: Contains smaller datasets used in the analyses.
* **/hypothesis_1_entropy/**: Simulations and analysis for "Thermodynamic Projection as Entropic Illusion."
* **/hypothesis_2_constants/**: Analysis of astrophysical data to detect variations in fundamental constants (G, α, ħ, c).
* **/hypothesis_3_quantum_lod/**: Simulations for "Condensed Matter as LOD from Quantum Backreaction."
* **/hypothesis_4_biology/**: Bioinformatics pipeline and statistical analysis for "Macro-Evolution as Epistemological Misnomer."

## Installation and Setup

To replicate the analyses, you will need to set up the computational environment.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/IIMParadigm/The-IIM-Experiments.git](https://github.com/IIMParadigm/The-IIM-Experiments.git)
    cd The-IIM-Experiments
    ```

2.  **Create a Python virtual environment (recommended):**
    ```bash
    python -m venv iim-env
    source iim-env/bin/activate  # On Windows use `iim-env\Scripts\activate`
    ```

3.  **Install Python dependencies:**
    This project uses multiple distinct software environments. Each hypothesis folder that requires a specific set of Python libraries contains its own `requirements.txt` file. You must install the dependencies for each part of the analysis you wish to run.

    For example, to run the analysis for Hypothesis 1, navigate to that folder and install its dependencies:
    ```bash
    cd hypothesis_1_entropy
    pip install -r requirements.txt
    ```
4.  **Install external software:**
    Some analyses require specialized scientific software that cannot be installed with pip. Please see the README file within the `/hypothesis_4_biology/` folder for instructions on installing **OrthoFinder, MAFFT, and IQ-TREE**.

## Data Acquisition

The smaller datasets (e.g., the species-pair comparison data) are included in the `/data/` directory.

The large public datasets (NANOGrav, GWOSC, NCBI GenBank, etc.) must be downloaded separately. We have provided links and instructions in the README file within each relevant hypothesis folder.

## How to Cite

If you use the code or data from this repository in your research, please cite the original paper:

```
[Your Name(s)]. (Year). "Reclaiming Purpose in Science: Divine Teleology and the Irreducible Intent Model." [Journal or Preprint Server, e.g., arXiv:XXXX.XXXXX]
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
