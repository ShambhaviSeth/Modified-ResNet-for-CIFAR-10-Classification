﻿
# Modified ResNet for CIFAR-10 Classification

## Overview
This project presents a modified Residual Network (ResNet) architecture for efficient image classification on the CIFAR-10 dataset. By reengineering the traditional ResNet model, our implementation stays under the constraint of 5 million trainable parameters, achieving a substantial improvement in accuracy.

## Features
- *Custom ResNet Architecture*: Utilizes a customized ResNet-18 framework with fewer filters and additional residual blocks to optimize parameter efficiency.
- *Hyperparameter Tuning*: Incorporates advanced techniques like cosine annealing and ADAM optimizer for enhanced performance.
- *Data Augmentation*: Employs techniques such as horizontal flipping and color jitter to improve the model's robustness and generalization.

## Installation
bash
git clone https://github.com/ShambhaviSeth/Modified-ResNet-for-CIFAR-10-Classification.git
cd DeepLearningMiniProject
pip install -r requirements.txt


## Usage
To train the model with the default parameters:
python
python train.py

To evaluate the model on the CIFAR-10 test set:
python
python evaluate.py


## Results
The modified architecture achieves a test accuracy of approximately 91%, demonstrating the effectiveness of parameter management and architectural adjustments. Training and validation loss/accuracy curves are available in the Jupyter notebooks provided in the repository.

## Contributing
We welcome contributions from the community. Please refer to our contribution guidelines for more information on how to submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors
- *Shambhavi Seth*
- *Deepak Singh*
- *Aayush Agarwal*

## Acknowledgments
Special thanks to New York University for providing the resources and environment necessary for this research.

---

Feel free to modify or expand any sections as necessary to fit your project's specifics or your preferences.
