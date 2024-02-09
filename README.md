Automated Receipt Data Extraction and Conversion
Overview

Automating the process of converting receipt images into structured digital formats, our project leverages computer vision and machine learning to enhance financial management efficiency.Manual data entry from receipts is time-consuming and error-prone. Our solution automates this process, offering significant time savings, reducing errors, and improving overall efficiency in managing financial information.

We evaluated various OCR solutions, starting with pytesseract, and ultimately integrating LayoutLM for its superior accuracy in text extraction from complex receipt layouts.
Image Preprocessing: Critical to our OCR pipeline, preprocessing steps include resizing, grayscale conversion, Gaussian blurring, edge detection, contour identification, perspective transformation, and adaptive thresholding to prepare images for optimal OCR performance.
OCR Implementation and Contour Detection. Our system leverages pytesseract for initial exploration and LayoutLM for enhanced performance, achieving an impressive accuracy rate of around 90%. We also investigated contour detection methods, aiming to refine our approach for diverse receipt layouts.
Export to Excel. A key feature of our system is the ability to export extracted data into well-organized Excel files, automating the data entry process for financial management applications.

Future Directions:
- Develop bilingual support for English and Vietnamese text recognition.
- Design a real-time processing system for direct input from cameras or scanners.
