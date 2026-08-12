# EEG Dataset for Multiclass Depression Detection from Prefrontal EEG Signals

This repository contains the EEG datasets used in the study:

**“Multiclass Depression Detection from Prefrontal EEG Signals Using Deep Learning Models.”**

The repository contains:

1. **MODMA EEG dataset** — publicly available EEG data used in the study.
2. **Validation EEG dataset** — EEG recordings collected from five adult volunteers using an 8-channel EEG headset for validation of the proposed system.

## Repository Structure

```text
EEG_Depression_Detection_Dataset/
│
├── README.md
│
├── MODMA/
│   ├── README.md
│   └── EEG_3channels_resting_lanzhou_2015/
│
└── Validation_EEG/
    ├── README.md
    ├── V01.csv
    ├── V02.csv
    ├── V03.csv
    ├── V04.csv
    └── V05.csv
```

## MODMA Dataset

The `MODMA` directory contains the **EEG_3channels_resting_lanzhou_2015** dataset from the publicly available MODMA (Multi-modal Open Dataset for Mental-disorder Analysis) dataset.

The original MODMA dataset is described in:

> Cai, H. et al. A multi-modal open dataset for mental-disorder analysis. *Scientific Data* 9, 178 (2022).

**DOI:** https://doi.org/10.1038/s41597-022-01211-x

The MODMA dataset is a third-party dataset and is subject to the terms and conditions specified by the original data provider.

## Validation EEG Dataset

The `Validation_EEG` directory contains EEG recordings from **five adult volunteers** collected for validation of the proposed system.

The recordings were acquired using an **8-channel EEG headset** at a sampling rate of **250 Hz**. The recorded channels are:

`Fp1, Fp2, F3, F4, O1, O2, Fz, Pz`

The participants are identified using anonymous study-specific identifiers: `V01`–`V05`.

Written informed consent was obtained from all participants, including consent for public sharing of anonymized EEG data for research purposes.

Direct participant identifiers and system-generated identifiers, including Researcher ID, Experiment ID, Session ID, User ID, and Device ID, have been removed from the publicly shared files.

Each participant's recording is provided as a CSV file containing:

`pkt_num, Fp1, Fp2, F3, F4, O1, O2, Fz, Pz, timestamp`

## Citation

If you use the datasets in this repository, please cite the associated research article and the original MODMA data descriptor.

### Associated Research Article

**Multiclass Depression Detection from Prefrontal EEG Signals Using Deep Learning Models.**

### MODMA Dataset

Cai, H. et al. A multi-modal open dataset for mental-disorder analysis. *Scientific Data* 9, 178 (2022).

**DOI:** https://doi.org/10.1038/s41597-022-01211-x

## License

This repository is shared for academic and research purposes.
