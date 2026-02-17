# Design Document

## Architecture Overview

User → Prescription Upload  
→ OCR Engine  
→ NLP Medicine Extraction  
→ Brand-Generic Mapping Engine  
→ Price Comparison Module  
→ Savings Display  
→ Store Locator

## Tech Stack
- Frontend: HTML / React
- Backend: FastAPI (Python)
- OCR: AWS Textract / Tesseract
- Database: PostgreSQL
- Cloud: AWS (EC2, S3, RDS)

## Data Flow
Upload → Extract → Map → Compare → Display Results
