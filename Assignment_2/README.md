# Assignment 2

This folder contains the materials for Assignment 2. The assignment is divided into two parts: image filtering with OpenCV and image classification with a convolutional neural network (CNN) using PyTorch.

## Folder Contents

### 1. `image_filtering/`
This folder contains the notebook and image file used for Part 1 of the assignment.

Files:
- `image_filtering.ipynb` — Jupyter notebook for applying convolution kernels for edge detection and blurring
- `building2.jpg` — input image used in the filtering tasks

### 2. `build_cnn/`
This folder contains the notebook and supporting files used for Part 2 of the assignment.

Files:
- `build_cnn.ipynb` — Jupyter notebook for building, training, and evaluating the CNN on CIFAR-10
- `model_trained.pt` — saved trained model
- `cifar_data.png` — visualization/output image related to the dataset
- `data/` — CIFAR-10 dataset files used by the notebook

## How to Use the Code

### Requirements
The notebooks were run in Python 3 with Jupyter Notebook. Required libraries include:
- `opencv-python`
- `numpy`
- `matplotlib`
- `torch`
- `torchvision`
- `jupyter`

You can install the required packages with:

```bash
pip install opencv-python numpy matplotlib torch torchvision jupyter
```

### Running Part 1: Image Filtering
1. Open `image_filtering/image_filtering.ipynb` in Jupyter Notebook.
2. Make sure `building2.jpg` is in the same folder as the notebook.
3. Run the notebook cells in order.
4. The notebook will apply edge detection and blur kernels to the image and display the results.

### Running Part 2: CNN Classification
1. Open `build_cnn/build_cnn.ipynb` in Jupyter Notebook.
2. Make sure the required Python packages are installed.
3. Run the notebook cells in order.
4. The notebook will load the CIFAR-10 dataset, build the CNN model, train it, and evaluate test accuracy.
5. The trained model can be saved and reused through `model_trained.pt`.

## Notes
- The CNN notebook was trained on CPU.
- The saved model file is included for reference.
- If the CIFAR-10 dataset is not already present, the notebook may download it automatically depending on the notebook settings.

## Submission Contents
This submission includes:
- source notebooks for both parts
- supporting image/data/model files
- executed notebook outputs
- report materials for Assignment 2
