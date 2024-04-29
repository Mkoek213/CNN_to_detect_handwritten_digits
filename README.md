**README: Convolutional Neural Network (CNN) Model for MNIST Digit Recognition**

This repository contains a Convolutional Neural Network (CNN) model trained on the MNIST dataset for digit recognition. The model, referred to as `model_1`, achieves high accuracy on both the MNIST dataset and a custom dataset containing handwritten digits.

### Files Overview:

1. **model_1.ipynb**: This Jupyter Notebook contains the implementation of the CNN model (`model_1`) architecture for digit recognition on the MNIST dataset. It also includes training and evaluation code.

2. **test_on_MNIST_dataset.ipynb**: This Notebook provides data analysis and results of testing `model_1` on the MNIST dataset. The model achieved a validation accuracy of 99.5%.

3. **test_on_custom_dataset.ipynb**: Here, you can find data augmentation techniques applied to a custom dataset to resemble the MNIST dataset. Additionally, it demonstrates fine-tuning `model_1` on this custom dataset to improve performance.

4. **fine_tune_data/**: This directory contains custom samples used for fine-tuning `model_1` on the custom dataset.

### Instructions:

To replicate the results or experiment further with the model, follow these steps:

1. **Set Up Environment**:
   - Enter your virtual environment:
     ```
     conda activate <your_env>
     ```

2. **Open Jupyter Notebook**:
   - Start Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Navigate to the Notebook of interest (e.g., `model_1.ipynb`, `test_on_MNIST_dataset.ipynb`).

3. **Monitor GPU Performance**:
   - Watch GPU performance using the command:
     ```
     watch nvidia-smi
     ```

### Notes:

- The `model_1` architecture is designed for digit recognition tasks and achieves high accuracy on the MNIST dataset.
- Data augmentation techniques and fine-tuning can be applied to adapt the model to custom datasets or specific requirements.
- Further experimentation, such as adjusting hyperparameters or exploring different architectures, may be performed to improve performance or adapt the model to different tasks.

For any questions or issues, feel free to contact the repository owner. Happy experimenting!
