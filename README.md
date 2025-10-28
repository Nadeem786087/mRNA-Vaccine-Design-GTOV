# Computational Design of an mRNA Vaccine against Guanarito Mammarenavirus (GTOV)

##  Project Overview
This project involved the **computational design of a multi-epitope mRNA vaccine** against the Guanarito mammarenavirus (GTOV), the causative agent of Venezuelan hemorrhagic fever. The workflow combined immunoinformatics, structural biology, and bioinformatics tools to predict and validate epitopes that could elicit a strong and safe immune response.

**Key Achievement:** Designed a novel vaccine construct with high predicted antigenicity and immunogenicity, demonstrating a complete in silico vaccine design pipeline.

---

##  Methodology & Workflow

The project followed a structured computational pipeline:

### 1. Target Identification & Selection
- **Data Source:** NCBI Protein Database
- **Proteins Analyzed:**
  - Zinc-finger motif protein (NP_899220.1)
  - **Nucleocapsid protein (NP_899211.1)** - *Selected as the final target due to its surface exposure, high antigenicity, and non-allergenic properties.*
- **Tools:** ExPASy ProtParam, TMHMM, AllergenFP, VaxiJen.

### 2. Epitope Prediction & Selection
- **T-Cell Epitopes (MHC-I & MHC-II):** Predicted using IEDB analysis resource.
- **B-Cell Epitopes:** Predicted for humoral immune response.
- **Selection Criteria:** High antigenicity (VaxiJen), non-allergenicity (AllergenFP), non-toxicity (ToxinPred), and high immunogenicity.

### 3. Vaccine Construct Design
- **Process:** Selected T-cell and B-cell epitopes were combined using appropriate linkers (e.g., AAY, GPGPG) to form a single multi-epitope sequence.
- **Implementation:** Linker assembly and sequence finalization were performed using **Python** and **VS Code**.

### 4. Structural Biology & Validation
- **2D Structure Prediction:** PSIPRED
- **3D Structure Prediction & Modeling:** PHYRE2 for ab initio protein modeling.
- **3D Structure Refinement:** GalaxyWeb for energy minimization and improving model quality.
- **Model Selection:** Chose the refined model (Model-5) based on high GDT-HA score, low RMSD, and excellent Ramachandran plot statistics.

---

##  Technical Skills Demonstrated

| Category | Tools & Technologies |
| :--- | :--- |
| **Bioinformatics** | NCBI, ExPASy ProtParam, TMHMM, IEDB, PSIPRED, Phyre2, GalaxyWeb |
| **Immunoinformatics** | VaxiJen, AllergenFP, ToxinPred, Epitope Prediction & Analysis |
| **Programming & Data** | **Python** (for sequence manipulation), VS Code |
| **Conceptual Knowledge**| Vaccine Immunology, Structural Biology, Phylogenetics, Molecular Modeling |

---

##  Key Outcomes & Conclusions

- Successfully designed a **novel multi-epitope mRNA vaccine construct** against GTOV.
- The construct demonstrated **high antigenicity** and strong potential for immune activation (T-cell & B-cell response).
- Performed **full 3D structural modeling and refinement**, validating the stability of the vaccine protein.
- The project showcases a complete **in silico vaccine development pipeline**, from target selection to structural validation.

---

##  Authors

- **Muhammad Nadeem** - *Immunoinformatic Analysis, Epitope Prediction, Structural Modeling*
- Muhammad Usman - *[Team Member Role]*
- Danyal Abbas - *[Team Member Role]*
- Abdul Ahad - *[Team Member Role]*

*Submitted and Presentedto: Dr. Ayesha,Department of Bioinformatics and Biotechnology, Government College University Faisalabad.*
