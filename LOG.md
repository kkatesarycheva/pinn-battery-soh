# Build Log

## 2026-09-24
- Created GitHub repo and README stating the project goal (reproduce PINN4SOH
  on the XJTU battery dataset, then extend/evaluate).
- Cloned wang-fujin/PINN4SOH as the baseline repo. It already bundles
  processed CSVs per battery type (2C, 3C, R2.5, R3, RW, Sim_satellite —
  ~60 files total), so there may be no need to reprocess raw data at all.
- Separately downloaded the raw XJTU dataset from Zenodo (record 10963339,
  "Battery Dataset.zip", 2.3 GB) into Google Drive and unzipped it.
  Raw structure: Batch-1 through Batch-6 folders, plus a Chinese/English
  data-description PDF and a Temperature_Compensation_Data.mat file.
- Next: read the data-description PDF to understand the raw format, and
  check whether the repo's bundled CSVs are a fully-processed version of
  the same Batch data (in which case the raw download may just be a
  reference/backup) or something I still need to build myself.

## 2026-09-25
-
