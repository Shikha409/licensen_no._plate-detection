# # License Plate Detection and OCR Project
## Project Overview
This project leverages the power of YOLO (You Only Look Once) for detecting license plates in images and EasyOCR for extracting text from the detected license plates. The extracted text is then saved in a CSV file for further analysis or record-keeping.

## Features
License Plate Detection: Utilizes a pre-trained YOLO model to accurately detect license plates in images.
Text Extraction: Uses EasyOCR to read and extract text from the detected license plates.
CSV Export: Saves the detected license plate texts along with the image names into a CSV file.
## Installation
To run this project, you'll need to install the required Python packages. Use the following commands to install them:
Copy code

!pip install --upgrade ultralytics

!pip install ultralytics

!pip install easyocr

## Usage
Load YOLO Model: Load your trained YOLO model for license plate detection.
Create OCR Reader: Initialize the EasyOCR reader to read text from images.
Set Paths: Define the paths for your image folder and the CSV file where results will be saved.
Process Images: The script processes each image, detects license plates, extracts text, and saves the results to a CSV file.
## Script result 

![Cars100](https://github.com/user-attachments/assets/4ff0bbb3-a314-416c-8d50-203533976e06)

![Cars137](https://github.com/user-attachments/assets/3ee19fd9-4aab-4748-8019-97b059e1e435)

![csv](https://github.com/user-attachments/assets/e906d0c6-c160-4aa5-9462-1efee5736707)


## Load the YOLO model for license plate detection.
Set up paths for the folder containing images and the CSV file for saving results.
Create an EasyOCR reader instance.
Open the CSV file in write mode and write the header.
Iterate over all images in the folder, detect license plates, extract text from detected plates, and save the results in the CSV file.

## Notes
Ensure the paths to your YOLO model and image folder are correct.
The script checks if the file is an image based on its extension.
The results are saved in a CSV file with the image name and detected text.


## Conclusion
This project successfully integrates YOLO for accurate license plate detection and EasyOCR for efficient text extraction from detected plates
