# Dataset Information

## Bird Species Classification Dataset

### Dataset Overview

This dataset was created for a bird species classification project using deep learning and transfer learning. The dataset contains images of three bird species: Eagle, Flamingo, and Owl. The images were prepared and organized for image classification using transfer learning models.

### Dataset Statistics

- **Total Images:** 1,234

- **Number of Classes:** 3
  - Eagle: 599 images
  - Flamingo: 189 images
  - Owl: 446 images

### Dataset Split

The dataset was divided into training, validation, and testing sets using a 70:15:15 ratio.

- Training: 863 images (70%)
- Validation: 185 images (15%)
- Testing: 186 images (15%)

### Data Collection

Images were collected from online bird image sources and organized into separate folders according to their species. Duplicate and corrupted images were removed to improve dataset quality and ensure better model performance.

### Data Preprocessing

Before training, the following preprocessing techniques were applied:

- Resized all images to 224 × 224 pixels
- Converted images to RGB format
- Normalized pixel values using rescaling (1/255)
- Applied data augmentation during training:
  - Rotation
  - Horizontal Flip
  - Zoom
  - Width Shift
  - Height Shift

### Training Configuration

- Image Size: 224 × 224
- Batch Size: 32
- Epochs: 50
- Number of Classes: 3

### Models Used

The following transfer learning models were trained and evaluated:

- ResNet50
- DenseNet121
- MobileNetV3Large

### Evaluation Metrics

The models were evaluated using:

- Accuracy
- Mean Average Precision (mAP)
- Confusion Matrix
- Training Time

### Note

The dataset and trained model files are stored in Google Drive and are not included in this GitHub repository due to file size limitations.
