# [Official Guide] GK2A Data Processing Resources

This document provides a structured overview of the software, sample data, and ancillary datasets for Geo-Kompsat-2A (GK2A), managed by the National Meteorological Satellite Center (NMSC).

---

 1. Sample Data & Code

# ■ Sample Data
- gk2a_ami_le1b_sw038_fd020ge_202201010000.nc

# ■ Sample Code
- Python: Source Code / Description (PDF)
- Fortran: Read_AMI.f90 / SenPlanck_Gk2a.f90

---

 2. Ancillary Data

# ■ GEOS Projection
- Instruction File: readme_latlon.txt

| Area | 500m | 1km | 2km | Total Resolution |
| :--- | :---: | :---: | :---: | :---: |
| Full Disk | NC / BIN | NC / BIN | NC / BIN | NC / BIN |
| Extended Local Area | NC / BIN | NC / BIN | NC / BIN | NC / BIN |

# ■ LCC Projection
| Area | 500m (NC/TXT) | 1km (NC/TXT) | 2km (NC/TXT) | Total Resolution |
| :--- | :---: | :---: | :---: | :---: |
| East Asia | Available | Available | Available | Available |
| Korea | Available | Available | Available | Available |
| Typhoon | Available | Available | Available | Available |
| Extended Local Area | Available | Available | Available | Available |

---

 3. Calibration & Spectral Response Function (SRF)

# ■ Calibration Table
- Version 3.1: 20191115_gk-2a_ami_calibration_table_v3.1
- Version 3.0: 20190415_gk-2a_ami_calibration_table_v3.0

# ■ Spectral Response Function (SRF)
- GK2A_AMI_SRF.zip (Full 16 Bands)

---

 4. Land/Sea Mask
- Resource Pack: gk2a_LSMask.zip
- Instruction: readme_landsea.txt

| Area | 500m | 1km | 2km | Total Resolution |
| :--- | :---: | :---: | :---: | :---: |
| Full Disk | Provided | Provided | Provided | Provided |
| Extended Local Area | Provided | Provided | Provided | Provided |
| Local Area | Provided | Provided | Provided | Provided |

---
Data Source: Korea Meteorological Administration (KMA) / National Meteorological Satellite Center (NMSC)
