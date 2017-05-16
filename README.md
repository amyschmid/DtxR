# DtxR gene regulatory network modeling in *Halobacterium salinarum*

Code repository describing ANOVA and Boolean modeling of DtxR gene regulatory network in the paper entitled **"A transcription network of interlocking positive feedback loops maintains intracellular iron balance in archaea."** Authors: Mar Martinez-Pastor, Andrew Lancaster, Peter D. Tonner, Michael W. W. Adams, Amy K. Schmid


# ANOVA modeling
Statistical model to infer TF-TF interregulatory network topology (paper Figure 4). Model is based on the statsmodels package (Seabold, J.S. and Perktold, J. (2010), Proceedings of the 9th Python in Science Conference, Austin, TX, USA, pp. 57-61.)

## Dependencies
- Python
- Packages
  - matplotlib
  - pandas
  - statsmodels
- Data: anovadata.csv
- Notebook: ANOVAanalysis-git.ipynb

## Instructions 
Evaluate code cells in the notebook to recapitulate Supplementary Table S4. 

# Boolean modeling
Logic model to predict TF-TF network dynamical properties (paper Figure 5). 
## Dependencies
- Python
- Packages
    - numpy 
    - matplotlib
- Notebook: dtxr-booleanmodeling.ipynb 

## Instructions
Evaluate code cells in the notebook to recapitulate Figure 5 and Supplementary Figure S1.

## Acknowledgements
- Thanks to Paul Magwene for Boolean modeling tutorials and helpful discussions.
- Thanks to National Science Foundation grants MCB-1417750 and MCB-1651117.



