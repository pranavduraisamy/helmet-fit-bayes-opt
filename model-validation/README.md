# Model Validation:

 - The Hybrid III ATD Headform and Neck model I used in this project was basically extracted from LSTC's De­tailed HY­BRID III 50th percentile beta version model. (You can find full model in [this](http://ftp.lstc.com/user/lstc-dummies/LSTC.H3_50TH.DETAILED.190217_BETA_IntermediateRelease.zip) page )

 - Since the model is labeled as a beta version in the LSTC model catalogue and was developed approx seven years ago, I did a validation study against experimental drop test data from the literature to ensure reliability.

 - Python codes I used for postprocessing can be found inside the respective folders

## Validation I [(h3-lateral-wo-helmet)](h3-lateral-wo-helmet)

 - [First validation literature](https://pmc.ncbi.nlm.nih.gov/articles/PMC5309928/) is side drop (freefall) of a physical HIII head and neck assembly from a height of 50cm.

 - Contains keyword file with completed setup, and nodout ascii file, incase if you want to directly look into the results without solving the model.

 - Boundary conditions were replicated exactly as specified in the literature.

 - I used linear acceleration curve and HIC values (from Figure 7c, 8c and Table 3, to be precise) for validating my model. Those curves were digitized using WPD4 and those exact project files could be found in the same folder.
