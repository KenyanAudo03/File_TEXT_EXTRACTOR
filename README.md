# File Text Extractor

A web-based tool to extract text from PDF, DOCX, TXT, PNG, and JPG files. It supports password-protected PDFs and uses OCR for images.

## Features
- Extract text from:
  - **PDFs** (with or without passwords)
  - **DOCX** files
  - **TXT** files
  - **Images** (JPG, PNG) via OCR
- Multi-page PDF support (select and view specific pages).
- Download extracted text as `.txt` file.
- Simple, user-friendly interface.

## Technology Stack
- **HTML/CSS/JavaScript**
- **[PDF.js](https://mozilla.github.io/pdf.js/)** for PDF extraction.
- **[Tesseract.js](https://tesseract.projectnaptha.com/)** for image OCR.
- **[Mammoth.js](https://github.com/mwilliamson/mammoth.js)** for DOCX extraction.

## How to Use
1. **Upload a file** (PDF, DOCX, TXT, JPG, PNG).
2. (Optional) Enter password for protected PDFs.
3. **Extract text** and download it.
4. View specific pages for multi-page PDFs.

## Setup
Clone the repository:
```bash
git clone https://github.com/KenyanAudo03/File_TEXT_EXTRACTOR.git
cd File_TEXT_EXTRACTOR  
```
Open `index.html` in your browser.

## License
[MIT](LICENSE)

---

Enjoy seamless text extraction!
