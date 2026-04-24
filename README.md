# kyc-ocr-verification
# KYC Automation using OCR

## Overview

This project demonstrates a basic KYC (Know Your Customer) automation system using OCR (Optical Character Recognition). The system extracts text from identity document images and validates key identity information such as PAN number.

## Objective

To automate identity verification by extracting and validating information from ID documents, reducing manual effort and improving efficiency.

## Approach

* Used OCR to extract text from image-based documents
* Converted extracted text into readable format
* Applied pattern matching (regex) to detect PAN number format
* Implemented validation logic to determine KYC status

## Workflow

Image Input → OCR Text Extraction → Text Processing → PAN Validation → KYC Decision

## Result

* Successfully extracted text from images
* Detected valid PAN formats when present
* Classified documents as "KYC Passed" or "Manual Review Required"

## Tools Used

Python, EasyOCR, OpenCV, Regular Expressions (Regex)

## Key Learning

* Learned how OCR can be applied in KYC systems
* Understood pattern-based identity validation
* Gained experience working with unstructured data

## Future Improvements

* Support multiple ID types (Aadhaar, Passport)
* Improve OCR accuracy with preprocessing
* Add face verification for advanced KYC

