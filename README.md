
# PSYC2015 – N400 ERP Analysis

This repository contains a reproducible Quarto report
examining semantic relatedness effects on the N400
event-related potential using ERP CORE EEG data.

## Requirements

- Python 3.11 or newer
- Quarto
- Python packages in requirements.txt

## Dataset

Download the N400 dataset supplied for PSYC2015.

Place the raw EEG recordings in:

data/raw/

The files should have names such as:
001_raw.fif.gz
002_raw.fif.gz

The raw EEG data are not stored in this GitHub repository.
Retain the original dataset licence with the data.

## Reproducing the report

1. Clone this repository:

   git clone https://github.com/kashishshah2/erp_analysis_report_ks.git

2. Open the repository folder.

3. Create and activate a Python environment.

4. Install the dependencies:

   python -m pip install -r requirements.txt

5. Place the raw EEG files in data/raw/.

6. Render the report:

   quarto render index.qmd

The analysis will preprocess the EEG recordings,
create epochs, calculate participant averages,
and generate N400 grand-average waveforms.

## Analysis parameters

- ERP component: N400
- Electrode: CPz
- Measurement window: 300–500 ms
- Conditions: Semantically related and unrelated words

## Reference

Kappenman et al. (2021).
ERP CORE: An open resource for human event-related
potential research.
https://doi.org/10.1016/j.neuroimage.2020.117465
