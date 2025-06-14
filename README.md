#  SETI Signal Detection | Deep Learning for Alien Signal Search

This is my Kaggle project focused on detecting potential extraterrestrial signals from radio telescope data using deep learning.  
The work is inspired by the [SETI Institute's Kaggle competition](https://www.kaggle.com/competitions/seti-breakthrough-listen) and aims to classify whether a signal is present in a given dynamic spectrum sample.

---

## Project Overview

- **Task**: Binary classification (signal present / not present)
- **Dataset**: 6-channel spectrogram images of radio frequency captures
- **Goal**: Build a robust deep learning model to detect anomalies indicative of potential extraterrestrial sources

---

##  Model Summary

-  **Model**: CNN architecture (e.g. EfficientNetB2)
-  **Preprocessing**: Normalization, channel stacking
-  **Validation**: Stratified GroupK-Fold
-  **Final Metric**: Accuracy / ROC AUC

---

##  Files

- `seti-final-project.ipynb` — main notebook with training & evaluation
- `README.md` — this file
- `requirements.txt` — list of required libraries
