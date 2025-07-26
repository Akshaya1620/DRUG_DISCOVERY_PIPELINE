
# Drug Discovery Pipeline

![Pipeline Diagram](assets/pipeline_placeholder.png)

## Overview
The **Drug Discovery Pipeline** is a Python-based framework designed to streamline early drug discovery workflows. It provides a **starter template for ligand docking**, **binding affinity prediction**, and **future integration with AI/ML models** to accelerate hit identification.

This pipeline is ideal for **bioinformaticians, computational chemists, and AI researchers** looking to combine traditional molecular docking techniques with modern data science.

---

## Key Features
- **Ligand Docking Scaffold:** Ready-to-use structure for docking simulations.
- **Binding Affinity Results:** Generates sample outputs for ligands.
- **Extensible AI/ML Integration:** Future-ready for deep learning models like **binding affinity prediction** or **QSAR modeling**.
- **Modular Design:** Easy to extend with AutoDock Vina, SwissDock, or RDKit.

---

## Tech Stack
- **Languages:** Python 3.8+
- **Libraries:** 
  - `pandas` (data handling)
  - `numpy` (planned)
  - `rdkit` (planned)
- **Docking Engines (Future):**
  - AutoDock Vina
  - SwissDock

---

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/<your-username>/Drug_Discovery_Pipeline.git
cd Drug_Discovery_Pipeline
pip install -r requirements.txt
```

---

## Usage
Run the pipeline:
```bash
python pipeline.py
```
Output:
```text
Ligand   Binding_Affinity
Ligand1       -7.5
Ligand2       -7.5
Ligand3       -7.5
```
A CSV file (`docking_results.csv`) will be generated with sample docking results.

---

## Project Structure
```
Drug_Discovery_Pipeline/
│-- pipeline.py           # Main docking and AI pipeline
│-- requirements.txt      # Python dependencies
│-- README.md             # Project documentation
│-- assets/               # Images (pipeline diagrams, docking results)
│-- .gitignore            # Files and folders to ignore
```

---

## Roadmap
- [ ] **Integrate AutoDock Vina** for real docking simulations.
- [ ] Add **QSAR models** for predicting activity scores.
- [ ] Deploy a **Streamlit dashboard** for interactive ligand screening.
- [ ] Add **SMILES/ligand library** support.

---

## Example Workflow Diagram
![Pipeline Example](assets/pipeline_placeholder.png)

---

## License
This project is released under the MIT License.

---

**Author:** Akshaya M N  
**Contact:** [LinkedIn](https://linkedin.com/in/akshaya-mn) | akshayamn179@gmail.com
