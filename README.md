## Omni Document Analyzer

Lightweight utilities for experimenting with OCR, metadata extraction and
storage in MongoDB. The project is structured as a Python package so the
modules can be invoked using the `-m` flag.

### Running the scanner

From the project root install dependencies and execute:

```bash
python -m app.scanner
```

The command above processes files placed in the `scans/` folder and stores
results under `processed/`. It requires a running MongoDB instance and, for
OCR, a local Tesseract installation (configure paths in `config.py`).

