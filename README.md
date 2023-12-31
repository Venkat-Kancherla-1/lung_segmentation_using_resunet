# Lung Segmentation with U-Net

![Lung Segmentation Example](example.png)

This project implements lung segmentation using a U-Net architecture with residual connections. Lung segmentation is a crucial step in medical image analysis, and this model helps identify the regions of interest within chest X-rays for various diagnostic purposes.

## Table of Contents

- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Dataset

The lung segmentation dataset is available in the `/kaggle/input/chest-xray-masks-and-labels/data/` directory. It includes lung images and their corresponding masks. The dataset was sourced from [source link or citation].

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone <https://github.com/Venkat-Kancherla-1/lung_segmentation_using_resunet.git>

## Usage

segmentation-with-res-u-net.ipynb contains the code for data preprocessing, model creation, training, and testing.
The test_on_image function allows you to visualize model predictions on test images.
The get_metrics function can be used to visualize training metrics.

## Results 
The lung segmentation model achieved an impressive accuracy of 98% on the test dataset, making it a robust tool for identifying lung regions within chest X-rays. You can see the resultant images in Results directory

## Dependencies
Python (>=3.6)
TensorFlow (>=2.0)
Numpy
Pandas
OpenCV
Matplotlib

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with clear, concise commit messages.
Push your branch to your fork.
Open a pull request to the master branch of this repository.

Here, I attached the kaggle link of my work https://www.kaggle.com/code/kancherlavenkat/segmentation-with-res-u-net