# Model Validation:

 - The Hybrid III ATD Headform and Neck model I used in this project was basically extracted from LSTC's De­tailed HY­BRID III 50th percentile beta version model. (You can find full model in [this](http://ftp.lstc.com/user/lstc-dummies/LSTC.H3_50TH.DETAILED.190217_BETA_IntermediateRelease.zip) page )

 - Since the model is labeled as a beta version in the LSTC model catalogue and was developed approx seven years ago, I did a validation study against experimental drop test data from the literature to ensure reliability.

 - Python codes I used for postprocessing can be found inside the respective folders

 - Each folder contains respective keyword file with completed setup, and nodout ascii file, incase if you want to directly look into the results without solving the model.

 - Boundary conditions were replicated exactly as specified in the literature.

## Validation I [(h3-lateral-wo-helmet)](h3-lateral-wo-helmet)

 - [First validation literature](https://pmc.ncbi.nlm.nih.gov/articles/PMC5309928/) contains side drop (freefall) of a physical HIII head and neck assembly from a height of 50cm.

 - I used linear acceleration curve (from Figure 7c to be precise) for validating my model. Those curves were digitized using [WPD4](https://apps.automeris.io/wpd4/) and those exact project files could be found in the same folder.

## Validation II [(h3-frontal-helmet)](h3-frontal-helmet)

 - This validation is mainly performed to verify my helmeted Hybrid III model.

 - [This literature](https://www.ircobi.org/wordpress/downloads/irc2000/pdf_files/2000_23.pdf) is about the influence of body mass on the head dynamics in falling headform tests. 
 
 - I used experimental results of the Hybrid III headform falling at 6 m/s, with impact at the frontal region (B, as per ECE R22-04).

 - Model is validated against linear and rotational acceleration curves (from Figure 5). Again I used [WPD4](https://apps.automeris.io/wpd4/) for digitizing those curves from literature and those exact project files could be found in the same folder.
