# Canada_construction_emissions_inventory

Author: Leopold Wambersie <br>
Thesis director: Claudiane Ouellet-Plamondon <br>
Department:   Départment de genie de la construction, École de technologie supérieure, Montréal, Canada <br>
Funding from : Canada Research Chairs Programme

This repository contains the code necessary to run the analyses presented in the paper 
"Developing a comprehensive account of embodied emissions within the Canadian construction sector".
The data itself can be found at: [https://zenodo.org/record/10233490](https://zenodo.org/records/10233490)

This repository contains 3 files: 
 - CanCons_OpenIO.py <br>
     This file is a modified version of OpenIO-Canada, available at https://github.com/CIRAIG/OpenIO-Canada.
     The modifications include additional functionalities (reverse engineering a global Z matrix) and changes
     to the way imports are taken into account.

 - CanCons_Analysis_notebook.ipynb <br>
      This file contains the bulk of the analyses. The notebook runs OpenIO then performs analyses on the
      resulting EEIO matrices, then exports the results to excel.
   
 - CanCons_workbook.xlsx <br>
      This excel workbook contains the data exportd from the notebook, as wall as additional analyses and
      formatting changes necessary to create useful figures and interpretable results.

