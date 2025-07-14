# episim-models
A repository of epidemic model instances

Each folder contains the required files to run the model for the selected engine:
Files:
 A0_initial_conditions_seeds.csv: file with the initial seeds for the simulation
 episim_config.json: file with all the parameters required to run the simulation
 metapopulation_data.csv: file with the population by strata for each area
 R_mobility_matrix.csv: file with the ratio of trips between each patch
 kappa0_from_mitma.csv: file the value of the mobility reduction for each date
 rosetta.csv: relates the id of the areas, with the index used in the code and with the ids of other models, for example: mitma-provinces-ccaa
 

Two engines:
-MMCACovid19
-MMCACovid19Vac

Models
-spain-catalonia
-spain-ccaa
-spain-madrid
-spain-mitma
-spain-provinces
-spain-single_patch
