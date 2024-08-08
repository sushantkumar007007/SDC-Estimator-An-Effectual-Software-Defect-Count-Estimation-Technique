**SDC-Estimator: An Effectual Software Defect Count Estimation Technique**

**Overview**
This repository contains the data, scripts, and results associated with the study on the SDC-Estimator, a novel approach integrating LSTM and attention mechanisms for cross-version defect prediction. The repository is organized into three main folders: `results`, `data`, and `scripts`.

**Repository Structure**

**1.** `results/`
This folder contains all the results produced during the study, including the following:
- Study Results**: All the key results used in the analysis presented in the study.
- Additional Results**: Some results are based on additional data that were not part of the study.

**2.** `data/`
This folder contains all the datasets used in the study:
- Study Data**: All datasets that are directly used in the analysis.
- Additional Data**: Some datasets that were not part of the final study but are included for reference.

**3.** `scripts/`
This folder contains all the Python scripts used for data processing, model training, and evaluation:
- `time_distribution.py`**: Implements time distribution functionality.
- `test_attension.py`**: Script to test the attention mechanism.
- `CBVP_with_attention.py`**: Main script that integrates LSTM with the attention mechanism for Cross-Version Defect Prediction (CVDP).
- `time_distributed_densenew.py`**: Implements a custom time-distributed dense layer.

**Requirements**
To run the scripts, you need to install the required Python packages. You can install all dependencies using the following command:

```bash
pip install -r requirements.txt
