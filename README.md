# Project Overview

This project provides an in-depth exploration of the GPT-2 model architecture through interactive Jupyter notebooks. It breaks down and analyzes each component of the model.

The Python notebook implements the GPT-2 model layer by layer.

This exploration was made possible by the excellent book, [Build a Large Language Model (From Scratch)](https://www.amazon.com/Build-Large-Language-Model-Scratch-ebook/dp/B0DGQXVK62) by Sebastian Raschka. The book is accompanied by a [GitHub repository](https://github.com/rasbt/LLMs-from-scratch) that contains the code for the book.

The architecture diagram and the attention diagrams in the notebook are from the book.

## Requirements

- Python 3.11

## Installation

1. Make sure you have Python 3.11 installed. You can check your Python version with:
   ```bash
   python --version
   ```

2. Create a virtual environment with Python 3.11:
   ```bash
   python3.11 -m venv .venv
   ```

3. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dependency Management

- `requirements.in` contains the direct dependencies
- `requirements.txt` is generated from `requirements.in` and contains all dependencies with pinned versions
- To update dependencies, edit `requirements.in` and run `pip-compile requirements.in`
