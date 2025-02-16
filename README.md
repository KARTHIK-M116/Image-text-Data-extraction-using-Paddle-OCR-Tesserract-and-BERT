# Image-text-Data-extraction-using-Paddle-OCR-Tesserract-and-BERT
Below is an example `README.md` file for your GitHub repository:

```markdown
# Image Text Extraction using Tesseract and BERT

This repository contains a Jupyter Notebook demonstrating how to extract text from images using [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) and then process the extracted text using a pre-trained [BERT](https://github.com/google-research/bert) model with the help of the [Hugging Face Transformers](https://github.com/huggingface/transformers) library.

## Contents

- `Image_Text_Extraction.ipynb`: The main notebook with code for text extraction and processing.
- `README.md`: This file.

## Prerequisites

- **Python 3.x**
- **Jupyter Notebook** or **Jupyter Lab**

### System Requirements for Tesseract
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) must be installed on your system.
  - On Ubuntu, you can install it using:
    ```bash
    sudo apt-get install tesseract-ocr
    ```
  - On Windows, download and install from the [Tesseract OCR project](https://github.com/tesseract-ocr/tesseract/wiki).

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/Image-Text-Extraction.git
cd Image-Text-Extraction
```

### 2. (Optional) Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install the Required Python Packages

You can install the dependencies using `pip`:

```bash
pip install pandas pillow pytesseract transformers torch
```

Alternatively, if you create a `requirements.txt` file, install via:

```bash
pip install -r requirements.txt
```

## Usage

1. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Open the `Image_Text_Extraction.ipynb` notebook.

3. Update the `DATASET_FOLDER` path and any sample image paths in the notebook to match your local environment.

4. Run the notebook cells to perform image text extraction and process the text with BERT.

## Customization

- **Dataset Paths:** Modify the `DATASET_FOLDER` variable in the notebook to point to your local dataset.
- **Sample Image:** Change the sample image file path if necessary.
- **BERT Model:** If desired, replace the pre-trained BERT model with another model by modifying the `process_text_with_bert` function.

## Acknowledgments

- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [Hugging Face Transformers](https://github.com/huggingface/transformers)
- [BERT](https://github.com/google-research/bert)
```
