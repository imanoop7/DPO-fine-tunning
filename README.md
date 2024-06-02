# DPO Fine-Tuning

Welcome to the `DPO-fine-tunning` repository! This project focuses on fine-tuning a pre-trained model using the Direct Policy Optimization (DPO) method. The main script for this process is encapsulated in the Jupyter notebook `DPO_fine_tunning.ipynb`.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Links](#links)

## Overview

This repository demonstrates how to fine-tune a pre-trained model using DPO. The pre-trained model used is `Ronal999/phi2_finance_SFT`, and the fine-tuned model is saved as `phi2_DPO`. The dataset used for this process is `Intel/orca_dpo_pairs`.

## Requirements

To run the fine-tuning process, you need the following dependencies:

- Python 3.8+
- Jupyter Notebook
- PyTorch
- PEFT (Parameter-Efficient Fine-Tuning)
- Datasets (Hugging Face)
- CUDA (for GPU support)

## Installation

Clone the repository and install the required packages:
    ```bash
    git clone https://github.com/imanoop7/DPO-fine-tunning/tree/main.git
    cd DPO-fine-tunning
    pip install -r requirements.txt

## Usage
Open the Jupyter notebook and follow the steps to fine-tune the model:

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
2. Open DPO_fine_tunning.ipynb in your browser.

3. Follow the instructions within the notebook to load the dataset, configure  
   the model, and initiate the fine-tuning process using DPO.

## Files
`DPO_fine_tunning.ipynb`: A Jupyter notebook detailing the steps for `fine-tuning the Ronal999/phi2_finance_SFT` model using the `Intel/orca_dpo_pairs` dataset and saving it as `phi2_DPO`.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Disclaimer
This project is intended for educational and informational purposes only. The fine-tuned models and methods demonstrated in this repository are not intended for production use without further testing and validation. Users should exercise caution and perform their own due diligence before deploying any models fine-tuned using this repository.

The creators and contributors of this project are not responsible for any damages or losses incurred from using the fine-tuned models. By using this project, you agree to assume all risks associated with its use.

---

## Links
Medium Article
Fine-Tuned Model on Hugging Face

---
Happy fine-tuning! If you have any questions or need further assistance, feel free to open an issue.




