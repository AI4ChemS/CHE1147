

# Project datasets

 Below is a table of suggested datasets from chemistry, biochemistry, and materials science that you can use for your course project:

 ---

| Dataset Name | Description | No. Datapoints | Data Format | Possible Tasks | Download |
|:-------------|:------------|:---------------|:------------|:---------------|:----------|
| **ESOL** | Water solubility data (log scale solubility in mols per litre) for common organic small molecules | 1,128 | SMILES | Regression (predicting log solubility) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **QM9** | Dataset of 12 properties (geometric, energetic, electronic, and thermodynamic) for stable organic molecules modeled using Density Functional Theory | 133,885 | SMILES, 3D coordinates | Regression (predicting properties, 12 possible) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **LIPO** | Experimental results of octanol/water distribution coefficient (logD at pH 7.4) | 4,200 | SMILES | Regression (predicting logD) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **Tox21** | Qualitative toxicity measurements for compounds on 12 different targets, including nuclear receptors and stress response | 7,831 | SMILES | Classification (multitask classification, toxicity) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **Band Gap** | Experimentally measured band gaps for inorganic crystal structure | 4,604 | Chemical Formula (Should use featurizers like MatMiner) | Regression, Classification (binary, semi-conducting or not) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **Perovskite** | Contains Perovskite structures and their formation energies | 18,928 | Structure and Composition | Regression (predicting formation energy) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **MP Metallicity** | Contains inorganic crystal structures from the Materials Project database labeled as metals or nonmetals | 106,113 | Chemical Formula (Should use featurizers like MatMiner) | Classification (binary, metal or non-metal) | [MoleculeNet](https://deepchem.readthedocs.io/en/latest/api_reference/moleculenet.html) |
| **NeurIPS Polymer** | For NeurIPS open polymer prediction competition, predicting 5 properties | 1,500 | SMILES | Regression (predicting properties, 5 possible) | [Kaggle](https://www.kaggle.com/competitions/neurips-open-polymer-prediction-2025/data) |
| **MP Metallic Glass** | Matbench v0.1 test dataset for predicting full bulk metallic glass formation ability from chemical formula. Retrieved from "Nonequilibrium Phase Diagrams of Ternary Amorphous Alloys," a volume of the Landolt-Börnstein collection | 5,680 | Chemical Formula (Should use featurizers like MatMiner) | Classification (binary, glass forming or not) | [Matbench](https://matbench.materialsproject.org/Leaderboards%20Per-Task/matbench_v0.1_matbench_glass/#dataset-info) |
| **EnzyExtract** | Experimental values of turnover numbers (kcat) and Michaelis constants (Km) for enzyme-substrate pairs | 176,463 | SMILES, enzyme sequence, pH, organism, temp, EC number | Regression (predicting log kcat, log Km, or log kcat/Km) | [GitHub](https://github.com/ChemBioHTP/EnzyExtract/tree/main) |