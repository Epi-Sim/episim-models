## Name 

**COVID-19 Madrid Model for the MMCACovid19 engine**.

## Description

This model was developed to simulate the spread of SARS-CoV-2 virus in Madrid in 2020. The metapopulation is defined using 283 areas, which exceed the 179 municipalities in the region. Larger municipalities, such as the city of Madrid, are divided into several areas. Some areas correspond to a single municipality, while others cover a group of municipalities.

## Provenance

The original dataset contains information from **Basic Health Zones** (zonas básicas de salud)  in the region of Madrid.

However, this dataset does not include population by age strata. To address this, we used municipality-level population data, which does include data by age. The process involved:
 1. Mapping Basic Health Zones to Municipalities:
    We obtained a correspondance between the Basic Health Zones and the Municipalities.
 2. Estimating Age-Strata Population:
    For each Basic Health Zone, we applied the age distribution ratios from its corresponding
    municipality to estimate the population by age strata.
