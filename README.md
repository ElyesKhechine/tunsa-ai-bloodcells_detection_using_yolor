# Multi-label Detection & Classification of White and Red Blood Cells in Microscopic Images

### TUNSA AI

**Technologies:** Python, YOLOR, CUDA, YOLOv5, PyTorch Wavelets, Roboflow, YAML, CSP, SPP, FPN, Tensorboard, Data Augmentation

## Introduction

This project, executed by TUNSA AI, focuses on the development of a robust pipeline for the detection and classification of blood cells in microscopic images. Leveraging advanced computer vision techniques and machine learning algorithms, our goal is to accurately identify and classify platelets, red blood cells, and white blood cells in medical images.

## Project Scope

The project, undertaken from April 3, 2022, to May 8, 2022, entailed comprehensive research, experimentation, and model development phases.

## Technical Details

- **Custom Dataset Creation**: Developed a custom dataset using Roboflow consisting of 364 images, 4888 labels, and 3 classes (platelets, red blood cells, and white blood cells) in the YOLOv5 PyTorch export format.
- **Multi-Stage Computer Vision Model**: Implemented a multi-stage model incorporating CSP networks for cross-stage fusion, SPP for spatial refinement, YOLO heads for precise detection, and FPN for improved feature representation.
- **Model Training and Optimization**: Trained a YOLOR object detection model on a Tesla P100-PCIE-16GB GPU with CUDA acceleration for 50 epochs, achieving optimal performance with an overall loss of 0.3465 and an mAP of 0.85.
- **Training Monitoring and Evaluation**: Monitored training progress and evaluated model performance using Tensorboard, ensuring high accuracy and generalization through inference on augmented and ground truth training data.
- **Model Export and Deployment**: Exported the best-trained model weights for future use, ensuring reproducibility and enabling deployment in various medical imaging applications.

## Project Colab Link

Access the project's Colab environment for experimentation and further exploration: [Google Colab Link](https://colab.research.google.com/drive/1mxDiNOHu8rUWUC668QTRF_Y5eRJvdvik)


## Getting Started

### Installation

1. Ensure compatibility and setup of required hardware components and software dependencies.
2. Clone the project repository from GitHub.
3. Install necessary Python packages and dependencies specified in the requirements.txt file.

### Usage

1. Prepare input images for analysis and classification.
2. Run the provided scripts or notebooks to load the pre-trained model and perform inference on the images.
3. Analyze the results and fine-tune parameters as needed for specific applications.

## Contributing

Contributions aimed at enhancing project functionalities and addressing emerging challenges are encouraged.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).


## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
- Hamza Kalfat: hamzakalfat51@gmail.com
