# Learning Working on PDF

### PDF Types

- Farsi
- English

### PDF Types

- PDF content is text.
    - Select & Copy text and Paste somewhere else -> OK
    - Samples:
        - sample_01.pdf
        - sample_02.pdf
- PDF content is text.
    - Select & Copy text and Paste somewhere else -> NOT OK!
    - Samples:
        - sample_03.pdf
- PDF content is not text! It's Image!
    - Samples:
        - sample_04.pdf

### VSCode Extension

- vscode-pdf

### What is the best PDF libraries?

- https://pythonology.eu/what-is-the-best-python-pdf-library

### PyPDF Library

- https://pypi.org/project/pypdf
- https://github.com/py-pdf/pypdf
- https://pypdf.readthedocs.io/en/latest

### Pillow Library (Similar OpenCV)

- https://pypi.org/project/pillow
- https://python-pillow.github.io
- https://pillow.readthedocs.io/en/stable
- https://github.com/python-pillow/Pillow

### Pdf2Image Library

- https://pypi.org/project/pdf2image
- https://github.com/Belval/pdf2image
- Download the latest version of 'Poppler':
    - https://github.com/oschwartz10612/poppler-windows/releases
    - Create a folder, with the name of 'install'.
    - Put the zip file in 'install' folder.
    - Extract zip file in 'install' folder.
    - Rename the folder to just 'propper'.

### PyTesseract Library

- https://pypi.org/project/pytesseract
- https://github.com/madmaze/pytesseract
- https://github.com/tesseract-ocr/tessdata
- Download and Install 'tesseract-ocr-w64':
    - https://github.com/UB-Mannheim/tesseract/wiki
    - tesseract-ocr-w64-setup-5.5.0.20241111.exe (64 bit)
    - Install in below path:
        - C:\Program Files\Tesseract-OCR
    - https://github.com/UB-Mannheim/tesseract/releases
    - https://tesseract-ocr.github.io/tessdoc/Installation.html

##### Note

- In installation process
    - Choose Components Page:
        - In Additional language data (download)
            - Select: Persian

- Tesseract-OCR Path:

```bash
C:\Program Files\Tesseract-OCR
```

### Download Free PDF Files

- https://yes-pdf.com


### Setup Environment

```bash
python -m venv .venv
```

```bash
.\.venv\Scripts\activate
```

```bash
python -m pip list
```

```bash
python -m pip install -U pip
```

```bash
python -m pip install -U pypdf
```

```bash
python -m pip install -U pillow
```

- Note: After installing Pillow, We do not need to run below command!

```bash
python -m pip install -U pypdf[image]
```

```bash
python -m pip install -U pdf2image
```

```bash
python -m pip install -U pytesseract
```

- Just for Jupiter Notebook

```bash
python -m pip install -U ipython
```

```bash
python -m pip install -U ipykernel
```

```bash
python -m pip install -U ipywidgets
```

```bash
python -m pip list
```

Now! We Write / Modify / Delete / Run the Source Codes...

```bash
deactivate
```
