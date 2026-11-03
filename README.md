# Multi-PDFs ChatApp

A local Streamlit app for searching the contents of multiple PDF documents. PDF text is processed on your computer; no Gemini API key or internet connection is needed for document search.

## Features

- Upload and search one or more PDF files.
- Find matching passages locally and display the source filename and page number.
- Download the bundled `Augmented LLMs.pdf` from the app sidebar.
- Answer five curated questions about the sample PDF with concise, page-cited explanations.

The app returns relevant excerpts from the source PDFs rather than generating free-form answers with an LLM.

## Installation

Install the requirements:

```powershell
pip install -r requirements.txt
```

Run the app from this folder:

```powershell
streamlit run chatapp.py
```

## Usage

1. Upload one or more PDFs in the sidebar.
2. Click **Submit & Process**.
3. Enter a question to see relevant passages and their page numbers.
4. Use **Download Augmented LLMs PDF** in the sidebar to download the bundled sample PDF.
5. For the five prepared sample questions, use the matching question wording; answers are based on page 1 of the paper. Download the Q&A file from the sidebar.

Scanned/image-only PDFs may not contain extractable text and therefore may not be searchable.

## License

Distributed under the MIT License. See `LICENSE` for more information.
