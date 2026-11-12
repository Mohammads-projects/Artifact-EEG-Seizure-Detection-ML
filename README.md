# Artifact-Informed Multi-Domain Machine Learning Framework for Automated EEG Seizure Classification
Artifact-informed ML framework for automated EEG seizure classification using CHB-MIT and TUH datasets. Integrates feature stability analysis, mutual-information selection, and a probabilistic stacking ensemble (RF, XGB, LGBM with Logistic Regression), achieving 95.16% accuracy and 97.96% ROC-AUC.
# Datasets Used
CHB-MIT Scalp EEG Dataset : https://physionet.org/content/chbmit/1.0.0/

TUH EEG Artifact Dataset: https://isip.piconepress.com/projects/nedc/data/tuh_eeg/tuh_eeg_artifact/

Utilized for robust artifact-aware feature refinement and stability analysis. Incorporates major artifact classes:
eyem: Eye movement artifacts
musc: Muscle artifact activity
elec: Electrode pop/contact noise
chew: Chewing/jaw movement artifacts
