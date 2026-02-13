# North Atlantic Gyre Integrated Ocean Dataset (NAG-IOD)

## Overview

This repository supports our NSF proposal focused on building an **integrated physical–chemical North Atlantic gyre ocean dataset** by harmonizing multiple major oceanographic data sources.

Our goal is to construct a unified, research-grade dataset enabling:

- Large-scale ocean analysis  
- Gyre dynamics modeling  
- Physical–biogeochemical coupling studies  
- Data-driven ocean modeling  
- Machine learning applications in ocean science  

This repository demonstrates ongoing practical development and integration efforts.

---

## Scientific Motivation

The North Atlantic gyre plays a critical role in:

- Climate regulation  
- Carbon sequestration  
- Nutrient cycling  
- Biogeochemical transport  
- Ecosystem productivity  

Existing datasets are fragmented across physical, chemical, satellite, and reanalysis platforms. This project integrates heterogeneous sources into a coherent framework suitable for advanced modeling and AI-driven analysis.

---

## Data Sources

### 1. World Ocean Database (WOD – NOAA)
In-situ physical and chemical measurements  
🔗 https://www.ncei.noaa.gov/products/world-ocean-database

---

### 2. ORAS5 Reanalysis Dataset (ECMWF)
Ocean reanalysis dataset providing physical ocean state variables  
🔗 https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/oras5

---

### 3. BCO-DMO (NSF-funded repository)
Biological and Chemical Oceanography Data Management Office  
🔗 https://www.bco-dmo.org/

---

### 4. BGC-ARGO Floats
Global biogeochemical profiling float program  
🔗 https://biogeochemical-argo.org/

---

### 5. CMEMS (Copernicus Marine Service)
Operational marine monitoring and forecasting products  
🔗 https://marine.copernicus.eu/

---

### 6. NASA–ESA Ocean Color
Satellite-derived ocean color and chlorophyll products  
🔗 https://oceancolor.gsfc.nasa.gov/

---

### 7. CASCADE Dataset
Derived ocean dataset used for integration experiments  
🔗 [https://oceancolor.gsfc.nasa.gov/](https://github.com/nanophyto/CASCADE/releases/tag/v0.1.1)

---

## Current Status

Completed:

- ORAS5 ingestion and preprocessing  
- CASCADE ingestion  
- Initial ORAS5–CASCADE harmonization  
- Spatial and temporal alignment  
- Preliminary analysis (see notebooks)

In progress:

- BGC-ARGO integration  
- Satellite chlorophyll alignment  
- CMEMS physical–biogeochemical merging  

---

## Integration Framework

1. Data ingestion and metadata harmonization  
2. Spatial interpolation to North Atlantic gyre grid  
3. Temporal alignment and resampling  
4. Physical–chemical variable coupling  
5. Derived feature generation  
6. Validation and cross-dataset consistency checks  

---

## Reproducibility

All integration steps are documented in Jupyter notebooks.

This repository demonstrates technical feasibility and risk reduction in support of our NSF proposal.

---

## Proposal Reference

This repository supports our NSF proposal:

"Integrated Physical–Chemical North Atlantic Gyre Dataset for Advanced Ocean Analysis and Modeling"

Proposal link will be added upon submission.

---

## Contact

Majid Afshar  
Indiana State University  
majid.afsharnoghondari@indstate.edu

---

## License

