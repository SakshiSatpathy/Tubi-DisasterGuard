# Tubi-DisasterGuard

To process data:
1. Read in images (using cv2 or similar library)
2. Sample x amount of images from each folder
3. Extract file names and set them as "labels" of these photos
4. Now we have a list of images and labels
5. Scramble images (without labels) and split into train, validation, testsets
6. Run model on training set with associated targets (labels of classes)
7. Run confusion matrix and other metrics to get accuracy

To run code:
Run in Google Colab, unzip AIDER dataset from https://drive.google.com/drive/folders/1d3ByWH5HXSc0qr3Pe1e3OEgXxq6Z_y4R?usp=drive_link into Google Drive folder with all 3 code files.
