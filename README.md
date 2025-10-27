# PDF to Excel Converter & Merger

## Overview

This web application allows users to upload multiple PDF files, extract their textual content, convert that content into tabular Excel format, and merge all the extracted data into a single Excel sheet. The final merged Excel file can then be downloaded directly from the browser.

## Setup

1. Download the `index.html` file (the entire HTML code above).
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No server or installation is required as the app runs fully client-side.

## Usage

1. Click on the upload area or drag & drop one or more PDF files onto it.
2. The list of uploaded PDF files will appear below the upload area.
3. Click the **Convert & Merge to Excel** button.
4. The app will process each PDF, extract text, convert it into tables, merge all tables, and prompt you to download the merged Excel file named `merged_output.xlsx`.
5. Open the downloaded Excel file to view the combined data from all PDFs.

## Features

- Drag & drop or browse to upload multiple PDF files.
- Extracts text content from all pages of each PDF.
- Converts extracted text into tabular data using heuristics.
- Merges all tables from multiple PDFs into a single Excel worksheet.
- Generates and downloads the merged Excel file entirely in the browser.
- No server or backend required; fully client-side processing.
- Responsive and accessible UI with status updates.