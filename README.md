# episim-models
A repository of epidemic model instances.
Each folder contains the required files to run a specific model using of the supported simulation engines.

##File Structure
Each model diectory typically includes the following files:

 - `A0_initial_conditions_seeds.csv`: Initial seeds values for the simulation.
 - `initial_conditions.nc`: Initial compartments values in NetCDF format.
 - `episim_config.json`: Configuration file containing all the parameters required to run the simulation.
 - `metapopulation_data.csv`: Population data by age strata for each patch.
 - `R_mobility_matrix.csv`: Ratio of trips between patches.
 - `kappa0_from_mitma.csv`: Time-varying mobility reduction factors derived form MITMA data.
 - `rosetta.csv`: Mapping between the internal indexes and external identifiers (e.g. MITMA areas, provinces, autonomous communities)
 

##Supported Engines
- MMCACovid19
- MMCACovid19Vac

##Available Models
- catalonia-seccen (sección censal)
- madrid-zonbas (zonas básicas de salud)
- spain-mitma (MITMA mobility areas)
- spain-provinces
- spain-ccaa (Autonomous Communities)
