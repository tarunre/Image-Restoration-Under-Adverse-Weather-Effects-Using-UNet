# Image Restoration Using U-Net

A deep learning project that uses the **U-Net** architecture to restore degraded images by removing distortions such as fog, haze, or noise. The model is implemented using **PyTorch** and trained on paired image datasets to reconstruct high-quality images.

---

## Features

- Image restoration using U-Net architecture
- Custom dataset loading with PyTorch
- Image preprocessing and augmentation
- Model training and validation
- Performance evaluation using loss metrics
- Restore degraded images with a trained model

---

## Tech Stack

- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib
- PIL (Python Imaging Library)
- Jupyter Notebook

---

## Project Structure

```
Image-Restoration-Using-UNet/
│
├── Untitled6.ipynb          # Main notebook
├── datasets/                # Training and testing images
├── models/                  # Saved model weights (.pth)
├── outputs/                 # Restored images
├── requirements.txt         # Python dependencies
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Image-Restoration-Using-UNet.git
cd Image-Restoration-Using-UNet
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Prepare the training and testing datasets.
2. Open the Jupyter Notebook.
3. Run all notebook cells sequentially.
4. Train the U-Net model.
5. Save the trained model.
6. Test the model on degraded images.
7. View the restored output images.

---

## Model

The project implements the **U-Net** convolutional neural network consisting of:

- Encoder (Downsampling path)
- Bottleneck
- Decoder (Upsampling path)
- Skip Connections for preserving image details

---

##Results

The trained model successfully restores degraded images by learning mappings from corrupted inputs to clean target images.

Typical evaluation metrics include:

- Training Loss
- Validation Loss
- Visual comparison of input and restored images

---

## Future Improvements

- Improve restoration quality using Attention U-Net
- Train on larger datasets
- Add support for multiple degradation types
- Deploy as a web application using Flask or Streamlit

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.
