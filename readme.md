### Dataset : [Download Zip Folder](https://1drv.ms/u/s!AprPvJsuY4ejlR4b6WjjPBtSsn0t?e=JsczOF)

# Semantic Segmentation Models

This repository contains various U-Net model variations for semantic segmentation. Each model can be used to segment objects in images.

## Prerequisites

Before running the models, make sure you have the following:

- Python (3.6+)
- TensorFlow (2.0+)
- Other required libraries (list any additional libraries)

## Usage

Follow these steps to run the models:

1. Clone the repository to your local machine.

2. Navigate to the project directory:

3. Create a virtual environment (optional but recommended)

4. Install the required dependencies.

5. Run the U-Net models:

    - Model 1: U-Net with Batch Normalization
    
    ```
    python run_model.py --model bn
    ```

    - Model 2: U-Net without Batch Normalization

    ```
    python run_model.py --model no_bn
    ```

6. Monitor training progress and evaluate the model performance.

## Customization

You can customize the models by modifying the code in `Homework_3_Normalization(1).pynb` or `Homework_3_Without_Normalization.pynb` . Adjust the model architecture, loss function, hyperparameters, and data preprocessing to suit your specific project requirements.

## Contributing

Feel free to contribute to this project by creating pull requests or reporting issues. We welcome contributions and improvements.







