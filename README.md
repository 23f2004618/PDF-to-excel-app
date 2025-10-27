# PDF to Excel Converter & Merger

## Overview

This web application allows users to upload one or more PDF files, extract their textual content, convert that content into tabular Excel format, and either save a single file's data as an Excel file or merge multiple PDFs' data into a single Excel sheet. The final Excel file can be downloaded directly from the browser without any server involvement.

## Setup

1. Download the `index.html` file.
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No server or installation is required as the app runs fully client-side.

## Usage

1. Click on the upload area or drag & drop one or more PDF files onto it.
2. The list of uploaded PDF files will appear below the upload area.
3. Click the **Convert & Merge to Excel** button.
4. If only one PDF file is uploaded, the app converts it and downloads an Excel file named after the PDF file with `_converted.xlsx` appended.
5. If multiple PDF files are uploaded, the app merges all extracted tables into a single Excel sheet and downloads it as `merged_output.xlsx`.
6. Open the downloaded Excel file to view the extracted and converted data.

## Features

- Drag & drop or browse to upload one or multiple PDF files.
- Extracts text content from all pages of each PDF.
- Converts extracted text into tabular data using heuristics.
- Saves a single PDF's data as an individual Excel file.
- Merges multiple PDFs' tables into one Excel worksheet.
- Generates and downloads the Excel file entirely in the browser.
- No server or backend required; fully client-side processing.
- Responsive and accessible UI with status updates.

## Improvements

- Added support for saving Excel files for single PDF uploads without merging.
- The downloaded Excel file is named after the original PDF file for single files.
- For multiple files, the previous merging behavior is preserved.
- Improved status messages to reflect single vs multiple file processing.
- Maintained all previous features including drag & drop, text extraction, and merging.