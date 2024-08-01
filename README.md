# Table-Extraction-ScienceGPT

- Make sure you have ```poppler``` and ```tesseract``` installed.

## Installation Instructions for Mac

```bash
brew install tesseract poppler
```

## Installation Instructions for Windows

### Tesseract
1. Download the Tesseract installer from https://tesseract-ocr.github.io/tessdoc/Downloads.html

### Poppler
1. Go to the Poppler for Windows GitHub releases page: https://github.com/oschwartz10612/poppler-windows/releases

2. Download the latest release (e.g., poppler-21.03.0-x86_64.7z).
3. Extract the downloaded file:
4. Open Git Bash.
5. Edit your .bashrc file to include the path to the Poppler bin directory. You can do this by running: 
```bash
 echo 'export PATH=$PATH:/c/poppler/bin' >> ~/.bashrc
```

6. Reload your .bashrc file: 
```bash
 source ~/.bashrc
```

## Next Steps
- Check out the [Table_Extraction.ipynb](./Table_Extraction.ipynb) file and run each cell carefully ONE BY ONE.