![image](https://github.com/user-attachments/assets/d1ba6aab-c7b0-46dc-9b66-6f8e9b6ea764)

# SMARTLAGOON Buoy Data Repository

This repository stores and provides access to the environmental monitoring data collected by the **SMARTLAGOON Buoy**, deployed in the **Mar Menor** coastal lagoon. The buoy is part of the **SMARTLAGOON** project, an initiative funded by the **European Union’s Horizon 2020 research and innovation programme (Grant Agreement No. 101017861)**. 

## 📌 About the SMARTLAGOON Project

**SMARTLAGOON** (Innovative Modelling Approaches for Predicting Socio-Environmental Evolution in Highly Anthropized Coastal Lagoons) is a Horizon 2020-funded project that integrates **real-time environmental monitoring, machine learning models, and social sensing** to assess and predict socio-environmental changes in the Mar Menor lagoon (Murcia, Spain).

The **SMARTLAGOON Buoy** contributes to the project’s objectives by **continuously measuring water quality and meteorological parameters**, providing valuable data to support **hydrodynamic and ecological modeling**, as well as **policy-making for sustainable lagoon management**.

## 📊 Data Description

The dataset includes **meteorological and water quality measurements** collected by the buoy at **hourly and daily intervals**. The following files are available:

| File Name | Description |
|-----------|------------|
| `2022-2023_60min.xlsx` | Hourly data collected during the initial deployment period (2022-2023). |
| `2023-2024_60min.xlsx` | Hourly data collected after buoy repair and redeployment (2023-2024). |
| `MarMenor_60min.xlsx` | Merged dataset from the two previous hourly data files. |
| `MarMenor_60min_QC.xlsx` | Quality-controlled version of `MarMenor_60min.xlsx` (recommended for use). |
| `2022-2023_Daily.xlsx` | Daily data from the initial deployment period (2022-2023). |
| `2023-2024_Daily.xlsx` | Daily data after the buoy redeployment (2023-2024). |
| `MarMenor_Daily.xlsx` | Merged dataset from the two previous daily data files. |
| `MarMenor_Daily_QC.xlsx` | Quality-controlled version of `MarMenor_Daily.xlsx` (recommended for use). |

🔹 **Note:** The QC (quality-controlled) files are the preferred datasets for analysis, as they have undergone **manual inspection and removal of suspect values**.

## 🌊 Measured Parameters

The SMARTLAGOON Buoy collects high-frequency **meteorological** and **water quality** measurements, including:

- **Meteorological Data:**
  - Air temperature (°C)
  - Relative humidity (%)
  - Wind speed (m/s)

- **Water Quality Data:**
  - Water temperature (°C) at multiple depths (0.5m, 1m, 2m, 3m, 4m, 5m, 6.5m)
  - Dissolved oxygen (mg/L) at different depths
  - Chlorophyll fluorescence (µg/L) as an indicator of algal biomass
  - Turbidity (NTU) to assess water clarity

## 📥 How to Access and Use the Data

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/smartlagoon-buoy-data.git
   cd smartlagoon-buoy-data

   
🏛 Acknowledgments

This work is part of the SMARTLAGOON project, which has received funding from the European Union’s Horizon 2020 research and innovation programme under Grant Agreement No. 101017861.

The SMARTLAGOON Buoy was developed and validated in collaboration with:
- CSIC-IEO
- Polytechnic University of Valencia
- Sensing Tools, S.L.
- Uppsala University
- VIELCA Ingenieros, S.A.

📜 License

This repository follows an open data policy under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. You are free to use, share, and modify the data as long as proper credit is given.
 
