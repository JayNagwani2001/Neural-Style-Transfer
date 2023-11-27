# Neural Style Transfer Notebook Setup and Execution

## Overview

This repository contains a Jupyter Notebook for performing neural style transfer using a custom VGG model. The notebook utilizes PyTorch and torchvision for deep learning operations.

## Installation

1. Install the required dependencies. It's recommended to use a virtual environment:

    ```bash
    pip install virtualenv
    virtualenv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

    The `requirements.txt` file includes necessary packages like PyTorch, torchvision, Pillow, and other dependencies.

## Usage

1. Open the Jupyter Notebook:

    ```bash
    jupyter notebook Dashtoon_Project.ipynb
    ```

2. Run the notebook cells sequentially:

    - Execute the cells for importing libraries and defining classes.
    - Load your content and style images by updating the file paths in the `load_image` function.
    - Run the remaining cells to perform neural style transfer and visualize the generated image.

3. Monitor the notebook output for loss values and generated image updates.

4. The final stylized image will be saved as "generated.png" in the project directory.

## Notes

- Ensure that you have GPU support if available, as neural style transfer can be computationally intensive.
- The notebook includes comments and explanations for each section, making it easy to follow the code and make customizations.
