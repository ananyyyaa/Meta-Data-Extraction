**AI/ML-Based Metadata Extraction**

This project implements an AI/ML system to automatically extract metadata fields from various document types, including .docx, .pdf, and scanned .png images. The system works irrespective of template or layout

**Solution**

This system uses a torch-free, lightweight AI-based metadata extraction system that uses unsupervised machine learninglightweight, AI-inspired alternative that avoids heavy dependencies like PyTorch or transformers.

**Pipeline Steps**

Preprocessing: Load test files based on filename prefix matching from test.csv

Text Extraction: Extract full text from .docx, .pdf, or .png using: python-docx PyPDF2 pytesseract (OCR for images)

Convert all document sentences and metadata labels into vectors.

Match each metadata label with the most similar sentence.

**Requirements**

Install these packages in a Python 3.10+ environment: pip install pandas python-docx PyPDF2 pytesseract pillow scikit-learn
Tesseract Installation 
