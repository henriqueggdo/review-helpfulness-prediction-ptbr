# Review Helpfulness Prediction for Brazilian Portuguese
This repository contains the implementation developed for my undergraduate thesis at the University of São Paulo (ICMC-USP).

The project investigates the task of review helpfulness prediction using the SteamBR dataset and compares two approaches:
  - Symbolic approach based on handcrafted textual features.
  - Sub-symbolic approach based on fine-tuning BERTimbau.

## Results
| Method  | F1-score |
| - | - |
| Symbolic  | 79.91%  |
| BERTimbau  | 86.51%  |

The results indicate that transformer-based models outperform handcrafted feature approaches, while symbolic methods provide greater interpretability.

## Repository Structure
- notebooks/: preprocessing, training and analysis notebooks.
- monograph/: undergraduate thesis document (in Brazilian Portuguese).
- results/: the model trained for the Sub-symbolic method.

## Dataset
This work uses the [SteamBR](https://github.com/germanojorge/SteamBR) dataset of Brazilian Portuguese Steam reviews.
