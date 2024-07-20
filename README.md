# 3-Layered Convolutional Neural Network (CNN) on FPGA
## Overview
This project demonstrates the implementation of a 3-layered Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset using the BASYS-3 FPGA board. The project was conducted under the mentorship of Prof. Joycee M. Mekie and Tom Glint during October-November 2022.

## Introduction
Convolutional Neural Networks (CNNs) are a class of deep learning algorithms that have shown significant success in image classification tasks. Implementing CNNs on FPGAs (Field-Programmable Gate Arrays) can achieve high performance and energy efficiency due to their parallel processing capabilities.

## Objectives
Implement a 3-layered CNN on the BASYS-3 FPGA board.
Classify images from the CIFAR-10 dataset.
Perform ReLU activation, max pooling, and convolution operations using Verilog.
Explore various CNN accelerators, such as the IRIS accelerator, to gain a deeper understanding of the field.
Hardware and Software Requirements
Hardware
BASYS-3 FPGA board
USB cables for programming and power
Computer with a USB port
Software
Vivado Design Suite for Verilog synthesis and implementation
Python for preprocessing and interfacing with the FPGA
CIFAR-10 dataset
## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 test images.


## Implementation Details
### Verilog Modules
#### Convolution Module

Implemented 3x3 convolution using sliding window technique.
Parallel processing to optimize computation time.
#### ReLU Module

Applied ReLU activation function (output = max(0, input)).
#### Max Pooling Module

Implemented 2x2 max pooling.
### Python Script
Preprocessed CIFAR-10 images.
Sent images to the FPGA for classification.
Received classification results from the FPGA.
Used Vivado IP Integrator for interfacing between Python and Verilog modules.
##CNN Accelerators
Researched various CNN accelerators such as the IRIS accelerator to understand optimization techniques for FPGA-based CNN implementations.
## Results
Successfully implemented a 3-layered CNN on the BASYS-3 FPGA board.
Achieved accurate classification results on the CIFAR-10 dataset.
Demonstrated the feasibility of FPGA-based CNN implementation for real-time image classification tasks.
## Future Work
Explore deeper CNN architectures for improved classification accuracy.
Implement optimization techniques such as quantization and pruning for efficient FPGA utilization.
Investigate other hardware platforms for CNN acceleration.
## Acknowledgements
We would like to thank Prof. Joycee M. Mekie and Tom Glint for their guidance and support throughout this project. Their expertise and insights were invaluable in the successful completion of this project.



