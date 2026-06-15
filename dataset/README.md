# Dataset Information

## Bird Species Classification Dataset

- **Total images:** 1,235
- **Classes:** 3
  - Eagle: 600  images
  - Flamingo: 189 images
  - Owl: 446 images

## Data Source
Images were collected using a **custom web crawler** built with Python.

### Web Crawler Tools Used:
- `requests` library for downloading images
- `BeautifulSoup` for parsing HTML
- `PIL/Pillow` for image processing
- `io.BytesIO` for handling image data

### Collection Process:
1. Searched for bird species images using web scraping
2. Downloaded images from multiple online sources
3. Filtered and validated images
4. Removed duplicates and corrupted files

## Dataset Split
- Training: 70% (~863 images)
- Validation: 15% (~185 images)
- Testing: 15% (~186 images)

## Data Preprocessing
- Standardized all images to 224×224 pixels
- Converted to RGB format
- Applied data augmentation (rotation, zoom, flip) during training

## Note
The full dataset is stored in Google Drive due to file size limits.
