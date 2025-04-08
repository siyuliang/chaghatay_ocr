# Chaghatay OCR Project

## Overview
This project is on Optical Character Recognition (OCR) for Chaghatay texts. It currently implements kraken and tesseract to process historical Chaghatay documents.

## Project Structure
```
chaghatay-ocr/
├── src/
│   ├── ocr scripts
├── data/
│   └── chaghatay files
└── output/
    └── OCR results
```

## About

### Kraken
Kraken is specialized for historical document processing and can be trained on specific scripts. The implementation in `kraken.ipynb` demonstrates how to process Chaghatay texts using this engine.

### Tesseract
Tesseract is a widely-used open-source OCR engine. The implementation in `tesseract.ipynb` shows how to configure and use Tesseract for Chaghatay text recognition.

## Data
The project includes a sample page from the ATMO corpus for testing purposes. Additional data can be added to the `data` directory.

## Output
OCR results are stored in the `output` directory, organized by engine and processing date.