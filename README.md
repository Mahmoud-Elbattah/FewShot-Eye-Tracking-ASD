# Few-Shot Learning with Pretrained Visual Embeddings of Eye-Tracking Patterns for Autism Detection

This repository contains the code accompanying our paper:

**Few-Shot Learning with Pretrained Visual Embeddings of Eye-Tracking Patterns for Autism Detection**

The study investigates few-shot classification of Autism Spectrum Disorder (ASD) from eye-tracking scanpaths. Scanpaths are converted into images, pretrained VGG-16 is used to extract visual embeddings, and two few-shot approaches are evaluated:

- Nearest Prototype classifier
- Supervised Contrastive Learning (SupCon)

Experiments consider 1-, 3-, 5-, and 10-shot settings using participant-level cross-validation.

## Pipeline

**Eye-tracking data → Scanpath images → VGG-16 embeddings → Few-shot learning → ASD/TD classification**

## Repository

- `FeatureExtraction.ipynb` – VGG-16 feature extraction
- `FSL_Prototype.ipynb` – Nearest Prototype experiments
- `FSL_SupCon.ipynb` – SupCon experiments
- `Classifier.ipynb` – supporting classification experiments

## Dataset

The eye-tracking dataset used in this study is publicly available on Figshare:

https://doi.org/10.6084/m9.figshare.20113592

## Citation

If you use this code in your research, please cite:

> M. Elbattah, F. Cilia, and G. Dequen,  
> “Few-Shot Learning with Pretrained Visual Embeddings of Eye-Tracking Patterns for Autism Detection.”

## Disclaimer

This repository is intended for research purposes only. The models are not clinical diagnostic tools.
