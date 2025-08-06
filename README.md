# P5 - Snap Random Forest Classifier: Maintenance

## Model Details

- **Type**: wml-hybrid_0.1
- **Model ID**: 725f4ec2-abf9-40...  <!-- Yahan poora Model ID daal dein -->
- **Software Specification**: hybrid_0.1
- **Hybrid Pipeline Software**: autoai-kb_rt24.1-py3.11
- **Created On**: Aug 3, 2025
- **Owner**: Vivek Chauhan
- **Last Modified**: 11 minutes ago by Service

## About

> This model was trained and deployed on IBM watsonx.ai Studio. The model is only available as a deployed asset. On IBM Cloud, there is no direct download option; it can only be used for inference via API.
## Usage
> The model is deployed as an API (the endpoint is available in the IBM Cloud deployment details).  
> You can make predictions by calling the API for inference—a sample Python code is provided in the `ibm_model_api_example.py` file.
## Notes

The training code or notebook is currently not available.

This repository is only for documentation and API usage samples of the deployed model.

# Predictive Maintenance with IBM AutoAI

This repository contains the Jupyter notebook **Predictive-Maintenance-Notebook.ipynb**, which demonstrates how to use IBM watsonx.ai AutoAI for automated machine learning workflows in predictive maintenance.

## Overview

- Set up and run experiments automatically
- Train and compare machine learning models
- Integrate with IBM watsonx.ai and IBM Cloud
- Deploy and score models easily

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Getting Started

### Prerequisites

- Python 3.11 or newer
- IBM watsonx.ai account with IBM Cloud API Key
- Jupyter Notebook or JupyterLab installed
- These Python packages:
    - ibm-watsonx-ai
    - autoai-libs
    - lale
    - scikit-learn==1.3.*
    - xgboost==2.0.*
    - lightgbm==4.2.*
    - snapml==1.14.*

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

If you have a `requirements.txt` file:
```bash
pip install -r requirements.txt
```
Or install manually:
```bash
pip install ibm-watsonx-ai autoai-libs~=2.0 lale~=0.8.3 scikit-learn==1.3.* xgboost==2.0.* lightgbm==4.2.* snapml==1.14.*
```

## Usage

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open **Predictive-Maintenance-Notebook.ipynb**.
3. Follow the steps in the notebook:
    - Connect with your IBM Cloud API Key
    - Run AutoAI experiments to train and compare models
    - Deploy the best model and use it for scoring new data

**Note:** You will be asked for your IBM Cloud API Key while running the notebook.


## License

Licensed Materials - Copyright © 2025 IBM  
This notebook is released under the ILAN License. See the notebook for details.

## Acknowledgments

- IBM watsonx.ai Team
- IBM AutoAI documentation and tutorials

