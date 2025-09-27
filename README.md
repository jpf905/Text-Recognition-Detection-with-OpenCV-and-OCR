# **Text-Recognition-Detection-with-OpenCV-and-OCR**
### **Description**
I am using **OpenCV** for image preprocessing and **OCR** techniques to demonstrate text detection and recognition from images.

<img width="664" height="211" alt="Quote" src="https://github.com/user-attachments/assets/019639ac-0c65-4b48-b037-344fcd4115b9" />



### **Background**

Optical Character Recognition (OCR) with OpenCV and an OCR engine (like Tesseract) is a computer vision technique used to detect and extract text from images or scanned documents.


*   **OpenCV** handles image preprocessing steps such as grayscale conversion, thresholding, noise removal, and contour detection, which improve text visibility and structure.
*   Once the text regions are isolated and cleaned, the processed image is passed to an **OCR** engine (e.g., Tesseract) that uses machine learning models to recognize and convert the visual patterns of characters into machine-readable text.


This pipeline is widely used for digitizing documents, license plate recognition, and automating data entry from images.


### **Libraries Used**
*   OpenCV
*   Pytesseract
*   Matplotlib


### **Procedure**
1. Import the required packages
2. Load the image
3. Display the original image
4. Extract text from the image
5. Draw bounding boxes around the detected text
6. Display the image with the bounding boxes


