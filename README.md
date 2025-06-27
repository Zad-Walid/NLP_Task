# NLP_Task

This repository contains  notebooks demonstrating various Natural Language Processing (NLP) tasks using different Python libraries and frameworks.

## Notebooks

- **Task_Transformer.ipynb**  
  Uses Hugging Face Transformers for NER, text summarization, and sentiment analysis.
- **Task_spaCy_NLTK (1).ipynb**  
  Uses spaCy and NLTK for Named Entity Recognition (NER) and Sentiment Analysis.

## Tools / Libraries Used

- **spaCy**: For tokenization, part-of-speech tagging, and named entity recognition.
- **NLTK**: For tokenization, POS tagging, chunking, and sentiment analysis (VADER).
- **transformers (Hugging Face)**:  
  - Pretrained models for NER (`dslim/bert-base-NER`)
  - Summarization (`facebook/bart-large-cnn`, `google/pegasus-xsum`)
  - Sentiment analysis (`siebert/sentiment-roberta-large-english`)
- **Python**: The programming language used for all code.

## Assumptions Made

- The required models and datasets (e.g., `en_core_web_sm` for spaCy, NLTK data, Hugging Face models) are available or will be downloaded at runtime.
- The code is run in an environment with internet access to download pretrained models and NLTK corpora.
- The input texts are in English.
- The user has a GPU available for faster inference with transformer models (optional, but recommended).
- All dependencies are installed as listed in `requirements.txt`.

## Setting Up a Virtual Environment

It is recommended to use a Python virtual environment to manage dependencies and avoid conflicts with other projects.

1. **Create a virtual environment** (replace `venv` with your preferred name):
    ```sh
    python -m venv venv
    ```

2. **Activate the virtual environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

3. **Install the required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Getting Started

1. Clone the repository or download the files.
2. Set up the virtual environment and install dependencies as described above.
3. Open the notebooks in Jupyter or VS Code and run the cells.

---
