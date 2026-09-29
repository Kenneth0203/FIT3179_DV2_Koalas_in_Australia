# Queensland Koala Hospital data

Source page: https://www.data.qld.gov.au/dataset/koala-hospital-data

Direct source CSV: https://data.des.qld.gov.au/__data/assets/file/0018/440433/koalabase-1996-2025.csv

Publisher: Queensland Department of the Environment, Tourism, Science and Innovation

Licence: Creative Commons Attribution 4.0

Source coverage: July 1996 to 30 June 2025

Retrieved: 2026-09-29

Raw records processed: 59,808

The Queensland portal states that this is a selection of raw records from KoalaBase and that a small number of duplicates and errors may exist. The compact CSVs here are derived summaries for the visualisation. They do not contain individual koala names or record-level locations.

## Files

- `qld_koala_hospital_annual.csv`: yearly record and condition counts. 2025 is a partial calendar year because source coverage ends 30 June.
- `qld_koala_hospital_conditions.csv`: counts of boolean condition/circumstance flags. A record can have several flags, so categories overlap.
- `qld_koala_hospital_fates.csv`: counts by published adult fate.
- `qld_koala_hospital_lga.csv`: record counts by published LGA plus mean coordinates from valid record locations. Mean coordinates are display anchors, not official LGA centroids.

- `qld_koala_hospital_rescue_grid.csv`: rescue-location counts aggregated to 0.1-degree cells for a compact density map.
- `qld_koala_hospital_release_flows.csv`: aggregated rescue-to-release coordinate pairs for a flow map. Only records with both valid coordinate pairs are included.

Use the source URL in the CSVs and this file for attribution. Do not describe these records as a koala population census.
