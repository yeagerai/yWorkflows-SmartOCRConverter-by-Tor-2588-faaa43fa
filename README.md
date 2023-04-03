
# SmartOCRConverter

Design a workflow for the SmartOCRConverter that includes: 1) Preprocessing the input image by resizing and converting it to grayscale, 2) Using Tesseract OCR API to extract text from the preprocessed image, and 3) Exporting the extracted text to a .txt file.
## Initial generation prompt
a workflow named ImageToTextConverter that performs the following steps:  First, a component that does image preprocessing with resizing and grayscale conversion. Then, a component that does OCR (Optical Character Recognition) receiving the input from the image preprocessing component and accessing the Tesseract OCR API. Finally, a component named TextExporter that performs exporting the recognized text to a .txt file from the outputs received from the image preprocessing and OCR components.

## Authors: 
- yWorkflows
- Tor#2588
        