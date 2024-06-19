<!-- <a href="https://colab.research.google.com/github/ribesstefano/PROTAC-Degradation-Predictor/blob/main/notebooks/protac_degradation_predictor_tutorial.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> -->

# Machine Learning-Based Classification of Hardware Trojans in FPGAs Implementing RISC-V Cores (Laokoon-ML)

This repository includes code for the paper: _"Machine Learning-Based Classification of Hardware Trojans in FPGAs Implementing RISC-V Cores"_.

## 📝 Abstract

Hardware Trojans (HTs) pose a severe threat to integrated circuits, potentially compromising electronic de- vices, exposing sensitive data, or inducing malfunction. Detecting such malicious modifications is particularly challenging in complex systems and commercial CPUs, where they can occur at various design stages, from initial HDL coding to the final hardware implementation. This paper introduces a machine learning-based strategy for the detection and classification of HTs within RISC-V soft cores implemented in Field-Programmable Gate Arrays (FPGAs). Our approach comprises a systematic methodology for comprehensive data collection and estimation from FPGA bitstreams, enabling us to extract insights ranging from hardware performance counters to intricate metrics like design clock frequency and power consumption. Our ML models achieve perfect accuracy scores when analyzing features related to both synthesis, implementation results, and performance counters. We also address the challenge of identifying HTs solely through performance counters, highlighting the limitations of this approach. Additionally, our work emphasizes the significance of Implementation Features (IFs), particularly circuit timing, in achieving high accuracy in HT detection.

## 📈 Reproducing Results

Code for reproducing the results of the paper is available in [notebooks/ht_classification.ipynb](this Jupyter notebook). The code is written in Python and uses the following libraries:

```
pandas
numpy
matplotlib
seaborn
xgboost
scikit-learn
umap-learn
```

## 📄 Citation

If you use this work in your research, please cite the following paper:

```
@inproceedings{ribes2024machine,
    author={Stefano Ribes. and Fabio Malatesta. and Grazia Garzo. and Alessandro Palumbo.},
    title={Machine Learning-Based Classification of Hardware Trojans in FPGAs Implementing RISC-V Cores},
    booktitle={Proceedings of the 10th International Conference on Information Systems Security and Privacy - ICISSP},
    year={2024},
    pages={717-724},
    publisher={SciTePress},
    organization={INSTICC},
    doi={10.5220/0012324200003648},
    isbn={978-989-758-683-5},
    issn={2184-4356},
}
```