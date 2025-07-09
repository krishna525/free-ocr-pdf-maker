# free-ocr-pdf-maker

Convert scanned PDFs into fully searchable, text-selectable documents using OCR — easily extract text from any PDF file.

---

## Features

- Upload your scanned PDF file  
- Automatically perform OCR (Optical Character Recognition)  
- Extract the recognized text into a `.txt` file saved alongside the PDF  
- Simple and fast Python interface  
- Uses free online OCR API  

---

## Installation

Install the package via pip:

```bash
pip install ocr2text

```

## Usage

```bash
import ocr2text

pdf_path = r""

# This will process the PDF, perform OCR, and save the text file in the same folder
ocr2text.convert_pdf_to_text_with_ocr(pdf_path)
```
