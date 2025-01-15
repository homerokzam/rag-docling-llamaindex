# RAG with Docling and LlamaIndex for Personal Documents

This repository demonstrates how to use **Docling** and **LlamaIndex** to build a RAG (Retrieval-Augmented Generation) system with personal documents in PDF format. The goal is to allow language models to access and process information stored locally in personal documents to answer questions accurately and efficiently.

---

## Repository Features

- **RAG for personal documents**: The code allows you to ask questions directly about the content of personal PDF documents.
- **Docling**: Used for document processing and analysis.
- **LlamaIndex**: Responsible for indexing and building an efficient data retrieval pipeline.

---

## Repository Files

- `README.md`: This documentation file.
- `run_first_prepare_data.ipynb`: A Jupyter Notebook dedicated to the preparation of data for the Retrieval-Augmented Generation (RAG) system.
- `run_second_qa.ipynb`: A Jupyter Notebook designed to implement the question-answering (QA) capabilities of the RAG system.

---

## Code Features

1. **Loading PDFs**: The code uses libraries to load and process files in PDF format.
2. **Content Indexing**: Documents are processed and indexed using LlamaIndex.
3. **Query and Response Generation**: It is possible to ask questions based on the content of the documents and obtain accurate answers.
4. **Simple Interface**: Implemented in Jupyter Notebook to facilitate execution and understanding of the workflow.

---

## Prerequisites

Make sure you have the following items installed in your environment:

1. **Python**: Version 3.12 or higher.
2. **Miniconda**:
   - Install Miniconda according to your operating system:
     - [Download Miniconda](https://docs.conda.io/en/latest/miniconda.html)
   - After downloading, follow the installation instructions available on the official website.

3. **VSCode**:
   - Download and install Visual Studio Code:
     - [Download VSCode](https://code.visualstudio.com/)
   - Install the recommended extensions:
     - **Python Extension**: For Python support.
---

## Como Configurar o Ambiente

1. Clone this repository:
    ```bash
    git clone https://github.com/homerokzam/rag-docling-llamaindex.git
    cd rag-docling-llamaindex
    ```

2. Create and activate the virtual environment using Miniconda:
    ```bash
    conda create -n venv-rag-docling-llamaindex python=3.12.7
    conda activate venv-rag-docling-llamaindex
    ```

3. Install the Jupyter kernel and dependencies:
    ```bash
    pip install ipykernel
    pip install -r requirements.txt
    ```

4. Open the repository in VSCode:
    ```bash
    code .
    ```

5. Ensure that the Python and Jupyter extensions are installed in VSCode.
6. Select the kernel of the virtual environment created in Jupyter Notebook.
7. Create the directories: database, input/pdfs, and input/mds.
8. Copy your files to the directory: input/pdfs.