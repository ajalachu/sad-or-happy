# Image Classification using TensorFlow

## Overview
This project performs image classification using TensorFlow and Keras. The model is trained on images stored in different class folders and learns to classify them automatically.

## Features
- Image preprocessing and validation
- Dataset loading using TensorFlow
- Data visualization
- Deep Learning image classification
- Training and prediction using Keras

## Dataset Structure

data/
├── happy/
│ ├── image1.jpg
│ ├── image2.jpg
│ └── ...
├── sad/
│ ├── image1.jpg
│ ├── image2.jpg
│ └── ...

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- OpenCV

Install dependencies:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/nithinganesh1/Image_Classification.git
cd Image_Classification
```

2. Place your dataset inside the `data` folder.

3. Run the notebook or Python script.

## Data Loading

```python
data = tf.keras.utils.image_dataset_from_directory('data')
```

The dataset is automatically loaded from class folders.

## Visualization

```python
fig, ax = plt.subplots(ncols=5, figsize=(20,20))
```

Displays sample images from the dataset.

## Output

- Detects image classes
- Trains a classification model
- Predicts labels for new images

## Project Structure

Image_Classification/
├── data/
├── notebooks/
├── model/
├── README.md


## License

This project is open source and available under the MIT License.
