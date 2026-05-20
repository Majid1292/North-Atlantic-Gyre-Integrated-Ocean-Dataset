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

### Completed integrations

✅ CASCADE biological dataset

✅ ORAS5 physical ocean reanalysis dataset

✅ NASA Ocean Color satellite products

### Planned integrations

⬜ World Ocean Database (WOD)

⬜ BGC-ARGO

⬜ BCO-DMO

⬜ CMEMS

⬜ Additional satellite-derived environmental products
---

## Integrated Data Sources

### Biological Data

**CASCADE**

Contains biological measurements including:

- Cell abundance

- Particulate Organic Carbon (POC)

- Particulate Inorganic Carbon (PIC)

- Related biological variables

Source:

https://github.com/nanophyto/CASCADE/tree/v0.1.1

---

### Physical Ocean Data

**ORAS5 Ocean Reanalysis**

Contains ocean physical variables including:

- Temperature

- Salinity

- Ocean current variables

- Physical ocean conditions

Source:

https://www.ecmwf.int/en/forecasts/dataset/ocean-reanalysis-system-5

---

### Satellite Data

**NASA Ocean Color**

Satellite-derived environmental variables including:

- Chlorophyll concentration

- KD490 (light attenuation coefficient)

- Ocean optical properties

- Derived light-related environmental variables

Source:

https://oceancolor.gsfc.nasa.gov/

---

## Current Integration Workflow

#### Step 1

Merge biological measurements from CASCADE datasets.

Notebook:

```text

01_merge_cascade_oras5.ipynb

```

Tasks:

- Load and preprocess CASCADE biological variables

- Load ORAS5 physical variables

- Perform spatiotemporal matching

- Merge biological and physical measurements

- Generate integrated dataset

---

#### Step 2

Integrate satellite-derived environmental information.

Notebook:

```text

02_merge_nasa_ocean_color_with_cascade_oras5.ipynb

```

Tasks:

- Load merged CASCADE–ORAS5 dataset

- Extract NASA Ocean Color products

- Match satellite observations

- Generate derived environmental variables

- Handle missing values through imputation

---

## Current Features Included

Examples of integrated variables include:

Biological:

- Cells per liter

- POC

- PIC

Physical:

- Temperature

- Salinity

- Current speed

Satellite-derived:

- Chlorophyll-a

- KD490

- Light-related proxy variables

Derived:

- Estimated environmental features

- Distance matching metrics

- Imputed variables


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

