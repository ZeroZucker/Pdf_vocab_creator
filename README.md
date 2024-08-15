# Vocabulary Builder Tool

## Overview

The Vocabulary Builder Tool is designed to assist with learning new vocabulary from PDFs. It extracts highlighted words from a PDF file and generates a `.docx` file containing the words and their translations. This tool is especially useful for language learners who want to focus on specific terms they've highlighted during their study.

## Features

- **PDF Annotation Extraction:** Extracts text from highlighted sections in a PDF.
- **Word Translation:** Automatically translates the extracted text into the desired language (engish to german is the default).
- **Document Generation:** Creates a `.docx` file with a table containing the original text and its translation side-by-side.

## Installation

Before using the tool, ensure you have the required Python libraries installed:

```bash
pip install pymupdf googletrans docx
