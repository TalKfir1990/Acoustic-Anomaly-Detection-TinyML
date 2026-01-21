# Acoustic Anomaly Detection for Predictive Maintenance using TinyML

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Platform](https://img.shields.io/badge/Platform-Edge%20Device-green)](https://www.arduino.cc/)

This repository contains the official implementation, source code, and training pipeline for the research paper:

> **"{Real-time Anomaly Detection in Aviation Composites: An Edge Computing Framework for Acoustic Tap Test"**

## 📥 Dataset Access (Raw Data)

The full acoustic dataset used in this study is hosted on **Zenodo**.

We provide the **raw, unprocessed audio recordings** to ensure full transparency and reproducibility of the research. Providing the raw data allows researchers to:
1. **Reproduce the entire pipeline:** From raw signal processing and feature extraction to model training.
2. **Conduct future research:** Use this domain-specific dataset as a benchmark for developing new signal processing techniques or anomaly detection algorithms.

**Access the dataset here:** **[(https://zenodo.org/records/18324677)]**

---

## 📂 Repository Structure

```text
├── Acoustic_Anomaly_TinyML_Pipeline.ipynb   # Main End-to-End pipeline (Preprocessing -> Training -> Evaluation)
├── requirements.txt                         # List of Python dependencies
└── README.md                                # Project documentation
