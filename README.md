# Gate_patient_dosi

```
GATE macro for patient dosimetry from CT and SPECT

Author: Maxime Chauvin, maxime.chauvin@inserm.fr
Last revision: 22-03-2020

Usage example:
  Gate -a [nb,1e5][job,1] mac/main.mac

Inputs:
  - data/GateMaterials.db
  - data/patient_CT.mhd
  - data/patient_CT.raw
  - data/patient_SPECT.mhd
  - data/patient_SPECT.raw
  - data/Schneider2000DensitiesTable.txt
  - data/Schneider2000MaterialsTable.txt

Outputs:
  - output/{job}_patient-Dose.mhd
  - output/{job}_patient-Dose.raw
  - output/{job}_patient-Dose-Squared.mhd
  - output/{job}_patient-Dose-Squared.raw
  - output/{job}_patient-Dose-Uncertainty.mhd
  - output/{job}_patient-Dose-Uncertainty.raw
  - output/{job}_stats.txt
```
