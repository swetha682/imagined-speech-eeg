# imagined-speech-eeg
# Imagined Speech EEG Classification

## 1. Project Overview

This project focuses on imagined speech recognition using Electroencephalography (EEG) signals. The objective is to investigate EEG signal patterns associated with imagined speech and develop a system capable of classifying different imagined words.

The project uses the **BCI Competition 2020 Track 3 – Imagined Speech Dataset**.

## 2. Dataset Information

| Parameter | Details |
|---|---|
| Dataset | BCI Competition 2020 – Track 3 |
| Signal Type | EEG |
| Number of Subjects | 15 (S1–S15) |
| Age Group | 20–30 years |
| Number of Classes | 5 |
| Number of Electrodes | 64 |
| Sampling Frequency | 256 Hz |
| Time Samples per Trial | 795 |
| Trial Duration | Approximately 3.1 seconds |

### Imagined Speech Classes

The dataset contains five imagined words or phrases intended for basic communication:

1. Hello
2. Help me
3. Stop
4. Thank you
5. Yes

## 3. Dataset Distribution

The dataset provides training and validation data for all 15 subjects.

| Dataset Split | Trials per Class per Subject | Total Trials |
|---|---:|---:|
| Training | 60 | 4,500 |
| Validation | 10 | 750 |
| **Total** | **70** | **5,250** |

Each subject contributes 300 training trials and 50 validation trials, with an equal number of trials across the five classes.

## 4. Dataset Source

The dataset is available through the Open Science Framework (OSF):

[BCI Competition 2020 – Imagined Speech Dataset](https://osf.io/pq7vb/)

## 5. Project Structure

```text
Imagined-Speech-EEG-Project/
│
├── README.md
│
├── 01.Dataset_Inspection.ipynb
│
├── dataset/
│
└── experiment_outputs/
    └── Dataset_Documentation/
```

## 6. Current Progress

- Dataset downloaded and organized.
- Dataset structure inspected.
- Training and validation files examined.
- Subject-wise and class-wise trial distributions verified.
- Electrode and signal information documented.

## 7. Planned Work

- EEG signal preprocessing.
- Single-electrode signal extraction.
- Wavelet transformation.
- Scalogram generation.
- Imagined speech classification using deep learning architectures.
- Performance comparison and evaluation.

## 8. Technologies

- Python
- Google Colab
- NumPy
- SciPy
- Pandas
- Matplotlib
- MNE
- PyWavelets
- TensorFlow / PyTorch

---

**Note:** The current repository documents the dataset and its inspection process. Model training and classification will be added in subsequent stages.
