# Laokoon-ML

This repository includes code for the paper: _"Machine Learning-based Classification of Hardware Trojans in FPGAs
Implementing RISC-V Cores"_.

## Abstract

Hardware Trojans (HTs) pose a severe threat to integrated circuits, potentially compromising electronic devices,
exposing sensitive data, or inducing malfunction. Detecting such malicious modifications is particularly
challenging in complex systems and commercial CPUs, where they can occur at various design stages,
from initial HDL coding to the final hardware implementation. This paper introduces a machine learningbased
strategy for the detection and classification of HTs within RISC-V soft cores implemented in Field-
Programmable Gate Arrays (FPGAs). Our approach comprises a systematic methodology for comprehensive
data collection and estimation from FPGA bitstreams, enabling us to extract insights ranging from hardware
performance counters to intricate metrics like design clock frequency and power consumption. Our ML models
achieve perfect accuracy scores when analyzing features related to both synthesis, implementation results,
and performance counters. We also address the challenge of identifying HTs solely through performance
counters, highlighting the limitations of this approach. Additionally, our work emphasizes the significance of
Implementation Features (IFs), particularly circuit timing, in achieving high accuracy in HT detection.