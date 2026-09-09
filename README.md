# Open Data Artifacts

This repository contains measurement data and plots associated with the key link-performance results of a double-blind conference submission. The materials are provided in support of an Open Data badge application.

## Repository structure

```text
Open_Data_Artifacts/
├── 27Gbps_Notch/
│   └── ConstellationDiagram/
├── 51Gbps_Loopback/
│   ├── ConstellationDiagram/
│   ├── DMT_RX/
│   └── DMT_TX/
└── ber_all.csv
```

## Included measurement cases

### 27Gbps_Notch

Measurement artifacts for the 27-Gb/s notched-channel case include:

- aggregate and per-case BER data;
- EVM and SNR-per-subchannel data;
- bit- and power-loading parameters;
- constellation data and histogram tables for the included QAM formats; and
- PNG plots for quick inspection.

### 51Gbps_Loopback

Measurement artifacts for the 51-Gb/s loopback case include:

- aggregate and per-case BER data;
- EVM and SNR-per-subchannel data;
- bit- and power-loading parameters;
- constellation data and histogram tables for the included QAM formats;
- timestamped DMT transmitter and receiver measurement data; and
- PNG plots for quick inspection.

## File formats

- `.csv`: human-readable processed data tables.
- `.mat`: MATLAB data files containing the corresponding numerical arrays and measurement records.
- `.png`: rendered plots and constellation diagrams for visual inspection.

## Using the artifacts

Start with `Open_Data_Artifacts/ber_all.csv` for the aggregate BER results. Use the case-specific CSV files for processed numerical values and the corresponding MAT files when access to the stored MATLAB arrays is required. The PNG files provide quick visual references for the supplied measurements.

## Scope

This public package contains only the Open Data artifacts. RTL, netlists, executable design models, and other Open Design materials are not included.

## Double-blind review

Identifying author and affiliation information has been removed from this working copy. Do not add author names, affiliations, e-mail addresses, funding acknowledgements, patent references, or identifying repository metadata during the double-blind review period.
