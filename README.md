# EEG Signal Denoising

This project applies advanced deep learning techniques to denoise EEG (Electroencephalography) signals, enhancing the quality of EEG data by removing noise and improving signal clarity. The LU-Net deep learning model is used to remove noise and artifacts, including EOG (Electrooculography) and EMG (Electromyography) signals. The model is trained using the **EEGdenoiseNet** dataset, and the denoised EEG data is later used for classification tasks for Alzheimer's disease detection. Performance is evaluated using metrics like correlation (corr) and relative root mean square error (RRMSE).

## Table of Contents

1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Dataset](#dataset)
4. [Evaluation Metrics](#evaluation-metrics)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

EEG signals often contain various types of noise, including artifacts like EOG and EMG, which can interfere with accurate analysis. This project focuses on using LU-Net to denoise EEG signals, removing these artifacts. The model is trained using the **EEGdenoiseNet** dataset and applied to clean EEG data. This denoised data is later used for Alzheimer's disease classification. The overall aim is to improve the diagnostic accuracy of EEG signals by removing unwanted noise and enhancing the clarity of the underlying brain activity.


## Key Features

- **EEG Signal Denoising with LU-Net**
- **Artifacts Removed:** EOG and AMG
- **Denoised EEG Data Used for Alzheimer's Disease Classification**
- **Evaluation Metrics**
- **Comparison with ICA**

## Dataset

The dataset used for training the model is **EEGdenoiseNet**, which includes EEG recordings with both clean and noisy signals. This dataset is used to train the LU-Net model for denoising.

## Evaluation Metrics

- **Correlation (corr)**
- **Relative Root Mean Square Error (RRMSE)**

## Results

- SNR vs. Correlation plots.
- SNR vs. RRMSE plots.
- Comparative analysis of LU-Net and ICA denoising performance.

## Contributing

Contributions to this project are welcome.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please see the LICENSE file for more information.
