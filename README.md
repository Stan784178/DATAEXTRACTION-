# Global Horizontal Irradiance (GHI) Visualization  
## CAMS Gridded Solar Radiation Dataset

---

## Overview

This notebook demonstrates how to **retrieve, process, and visualize Global Horizontal
Irradiance (GHI)** data using the **CAMS Gridded Solar Radiation** dataset provided by the
**Copernicus Atmosphere Data Store (ADS)**.

The main output of this workflow is a **time-resolved heatmap animation** of GHI,
exported as a **GIF file**, allowing visual inspection of the temporal evolution
of solar irradiance over the selected region and period.

---

## Data Source

- **Dataset:** CAMS Gridded Solar Radiation  
- **Provider:** Copernicus Atmosphere Data Store (ADS)  
- **Dataset identifier:** `cams-gridded-solar-radiation`  
- **Variable used:** Global Horizontal Irradiance (GHI)  
- **Data type:** Gridded reanalysis / derived solar radiation product  

This dataset provides spatially distributed solar radiation estimates suitable
for climate analysis and solar energy applications.

---

## Variable Description

### Global Horizontal Irradiance (GHI)

Global Horizontal Irradiance represents the **total incoming solar radiation**
received on a horizontal surface.

In this notebook:
- GHI data is extracted from the CAMS dataset
- Values are visualized spatially as a **heatmap**
- Temporal evolution is shown using an **animation**

---

## Methodology

The workflow implemented in the notebook follows these steps:

1. Install and configure the **Copernicus API client (`cdsapi`)**
2. Authenticate using a `.cdsapirc` configuration file
3. Access the CAMS gridded solar radiation dataset
4. Extract GHI data for a selected time period
5. Generate a heatmap for each time step
6. Create an animation showing the temporal evolution of GHI
7. Export the animation as a **GIF file**

---

## Output

The notebook produces the following output:

- **Animated heatmap (GIF)** showing GHI variation over time  
