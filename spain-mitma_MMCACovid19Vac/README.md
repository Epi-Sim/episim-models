##Name
**COVID-19 Spain Model in MITMA areas for the MMCACovid19Vac engine**

##Description
This model was developed to simulate the spread of SARS-CoV-2 virus in Spain in 2020. The metapopulation is defined using 2850 mobility areas that broadly correspond to municipalities, districts or groups of the later depending on the population density.

##Provenance
The source data of this model is the 2020 mobility dataset in Spain, provided by MITMA (Ministerio de Transportes y Movilidad Sostenible).
* The zoning system (MITMA zones) is bases on population density: municipalities are either aggregated or subdivided into mobility zones depending on their density.
* The population is derived from this dataset. MITMA provides detailed files with information on the number of individuals making 0, 1, 2, or more daily trips within each area. 
* To construct the mobility matrix, we selected home-to-work and work-to-home trips, which are assumed to represent the recurrent daily mobility patterns. For each pair of Mitma zones, we computed the ratio of trips from one zone to another, resulting in a normalized mobility matrix.


