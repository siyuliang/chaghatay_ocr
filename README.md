# Chaghatay OCR Project

## Overview
This project is on Optical Character Recognition (OCR) for Chaghatay texts. It currently implements kraken and tesseract to process historical Chaghatay documents.

## Project Structure
```
chaghatay-ocr/
├── src/
│   ├── jarring_scraping.ipynb    # Script for scraping Jarring manuscripts
│   ├── kraken.ipynb              # Kraken OCR implementation
│   ├── preprocessing.ipynb       # Preprocessing scripts for OCR
│   ├── tesseract.ipynb           # Tesseract OCR implementation
├── data/
│   ├── jarring_manuscripts_data  # Directory containing Jarring manuscripts
│   └── v1.jpg                    # Sample image for OCR processing
├── output/
│   ├── kraken_all_ara.txt        # Kraken OCR results for all Arabic text
│   ├── kraken_ara.txt            # Kraken OCR results for specific Arabic text
│   └── tesseract.txt             # Tesseract OCR results
└── README.md                     # Project documentation
```

## About

### Kraken
Kraken is specialized for historical document processing and can be trained on specific scripts. The implementation in `kraken.ipynb` demonstrates how to process Chaghatay texts using this engine.

### Tesseract
Tesseract is a widely-used open-source OCR engine. The implementation in `tesseract.ipynb` shows how to configure and use Tesseract for Chaghatay text recognition.

## Data
The project includes:
- A sample page (`v1.jpg`) from the ATMO corpus for testing purposes.
- Additional data in the `jarring_manuscripts_data` directory, which contains Jarring manuscripts for OCR processing.

## Output
OCR results are stored in the `output` directory, organized by engine and processing type:
- `kraken_all_ara.txt`: Kraken OCR results for all Arabic text.
- `kraken_ara.txt`: Kraken OCR results for specific Arabic text.
- `tesseract.txt`: Tesseract OCR results.