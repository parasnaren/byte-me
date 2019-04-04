# byte-me
Developing an Automised Scanning and Storage system, that implements OCR to extract text from a scanned RC Card and store the structured data into a Database.

# Data Flow

# Files

### Untitled1.py

Using OpenCV to capture contours of the image and detect boundaries of the RC Card. The Region Of Interest(ROI) is then found and converted into grayscale and stored for text extraction.

### matching.py

Using OCR to extract text from the image.
Regex matching of the text to extract information in a structured format.


# Libraries and Dependencies

Spyder

OpenCV

Tesseract

