# Image-text-Data-extraction-using-Paddle-OCR-Tesserract-and-BERT

```markdown
# Image Text Data Extraction using Paddle OCR, Tesseract, and BERT

This repository contains a Jupyter Notebook demonstrating how to extract text from images using [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR), [Tesseract OCR](https://github.com/tesseract-ocr/tesseract), and then process the extracted text using a pre-trained [BERT](https://github.com/google-research/bert) model via the [Hugging Face Transformers](https://github.com/huggingface/transformers) library.

## 📂 Dataset

The dataset used for this project is available on Google Drive:

🔗 **[Download Dataset](https://drive.google.com/drive/folders/1O8FcLbhiE19YOLIwZ5yPVpKobCh6P-yY?usp=drive_link)**

Once downloaded, extract and place the dataset in your preferred location. Then update the notebook's `DATASET_FOLDER` variable to point to that location.

## 📜 Contents

- `Image_Text_Extraction.ipynb`: The main notebook for text extraction and processing.
- `README.md`: This file.

## 🚀 Prerequisites

- **Python 3.x**
- **Jupyter Notebook** or **Jupyter Lab**

### System Requirements for OCR Tools
- **PaddleOCR**: Follow the [installation guide](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.6/doc/doc_en/installation_en.md) for setup.
- **Tesseract OCR**: 
  - On Ubuntu:
    ```bash
    sudo apt-get install tesseract-ocr
    ```
  - On Windows, download and install from the [Tesseract OCR project](https://github.com/tesseract-ocr/tesseract/wiki).

## 🛠️ Setup

### 1. Clone the Repository

```bash
git clone https://github.com/KARTHIK-M116/Image-text-Data-extraction-using-Paddle-OCR-Tesserract-and-BERT.git
cd Image-text-Data-extraction-using-Paddle-OCR-Tesserract-and-BERT
```

### 2. (Optional) Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Required Packages

Install the necessary Python packages:

```bash
pip install pandas pillow pytesseract transformers torch
```

For PaddleOCR, follow its [installation instructions](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.6/doc/doc_en/installation_en.md).

## 🎯 Usage

1. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

2. **Open the `Image_Text_Extraction.ipynb` Notebook.**

3. **Update the Dataset Path:**
   - Modify the `DATASET_FOLDER` variable in the notebook to the location where you extracted the dataset.

4. **Run the Notebook Cells:**
   - The notebook demonstrates image text extraction using both Tesseract (and optionally PaddleOCR) and processes the text with BERT.

## 🔧 Customization

- **Dataset Paths:** Adjust the `DATASET_FOLDER` variable to match your local dataset location.
- **OCR Options:** Choose between PaddleOCR or Tesseract by commenting/uncommenting the appropriate sections in the notebook.
- **BERT Model:** You can switch to a different pre-trained BERT model by modifying the `process_text_with_bert` function.

