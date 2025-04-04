# assignment_nitallahabad_scoreme_20214513

# PDF Table Extractor 🏗️➡️📊

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PDF Support](https://img.shields.io/badge/PDF-Tables%20Extracted-orange)

A production-grade Python tool for extracting tables from PDFs to Excel without using Tabula/Camelot or OCR. Designed specifically for financial documents, bank statements, and reports.

## Table of Contents 📑
- [Features](#features-)
- [Installation](#installation-)
- [Usage](#usage-)
  - [CLI](#command-line-interface)
  - [Python API](#python-api)
- [Configuration](#configuration-)
- [Examples](#examples-)
- [How It Works](#how-it-works-)
- [Troubleshooting](#troubleshooting-)
- [Benchmarks](#benchmarks-)
- [Contributing](#contributing-)
- [License](#license-)

## Features ✨

**Core Capabilities**
- 🪄 Intelligent table detection (bordered and borderless)
- 📑 Multi-page table stitching
- 🛠️ Three extraction strategies with auto-fallback
- 🧹 Automatic data cleaning and normalization

**Advanced Features**
- 🔍 Header detection with smart merging
- 📈 Excel formatting preservation
- 🚦 Error recovery mechanisms
- 📊 Batch processing support

**Supported Documents**
- Bank statements (tested with Punjab & Sind Bank, SCB)
- Financial reports
- Research papers
- Government forms

## Installation ⚙️

### Prerequisites
- Python 3.7+
- Tesseract OCR (only needed for image-based PDFs)

### Recommended Setup
```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/yourusername/pdf-table-extractor.git
cd pdf-table-extractor

# Create isolated environment
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows

# Install with pip
pip install -e .
