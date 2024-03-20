# Solution for Molecular Modeling and Biomedical Data Analytics Test Task

## Overview

This README documents my solution to a test task involving molecular modeling and analysis of biomedical data. The project focused on identifying a promising drug candidate for the treatment of Type 2 Diabetes Mellitus through in silico analysis and experimental validation.

## Methodology

- **Data Analysis:** Utilized Python and various libraries (Pandas, Seaborn, Matplotlib, Biopython) to analyze a dataset of ~100k drug candidates, narrowing down to 10 leads based on in silico parameters.
- **Hypothesis Formulation:** Developed a scientific hypothesis on the relationship between the predicted cellular activity of the leads against GLP-1R and GIPR receptors and their in silico descriptors. Additional descriptors like aromaticity and instability index were calculated using Biopython.
- **Experimental Validation:** Collaborated with a team to validate the hypothesis experimentally, assessing the cellular activity of the shortlisted molecules in vitro.
- **Molecular Dynamics (MD) Simulation:** Prepared, equilibrated, and conducted MD simulations using GROMACS to characterize the most promising molecule's stability and interactions with the target receptors.
- **Visualization:** Employed PyMOL and py3Dmol for 3D visualization of peptide ligands and their complexes with target receptors, ensuring a thorough structural understanding.

## Results

- The experimental results supported the initial hypothesis to some extent, revealing the complex nature of molecular interactions with receptors.
- The MD simulation and analysis indicated the stability of the selected lead compound in complex with the receptor, as evidenced by consistent RMSD values.

## Conclusion

The combined in silico and experimental approach provided valuable insights into the molecular basis of the selected lead's interaction with GLP-1R and GIPR receptors. This lead, identified through rigorous analysis, holds potential for further development in treating Type 2 Diabetes Mellitus.

## Additional Files

- 3D structures of the ligand and ligand-receptor complex
- Python notebooks and scripts used for data analysis and visualization
- MD simulation input and output files

For a more detailed walkthrough of the analysis, please refer to the Python notebooks included in the repository.
