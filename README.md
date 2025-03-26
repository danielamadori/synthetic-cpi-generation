# Synthetic CPI generation
![Python Version](https://img.shields.io/badge/python-3.12%2B-blue)
![GitHub issues](https://img.shields.io/github/issues/danielamadori98/synthetic-cpi-generation)
![GitHub pull requests](https://img.shields.io/github/issues-pr/danielamadori98/synthetic-cpi-generation)
![GitHub contributors](https://img.shields.io/github/contributors/danielamadori98/synthetic-cpi-generation)


## Description
This repository contains code and resources for generating synthetic data.

More details at [main.ipynb](https://nbviewer.org/github/danielamadori98/synthetic-cpi-generation/blob/main/main.ipynb)


## Prerequisites

- **Python 3.12+**

To install **Python**, follow the instructions on [Python's official website](https://www.python.org/downloads/).

---

## Quick Start

### Using Python
To start the application using Python, follow these steps:
1. **Environment Setup**
- **Using Conda**
    ```bash
    conda create --name cpi python=3.12
    conda activate cpi
    ```
- **Using venv**
    ```bash
    python3.12 -m venv cpi_env
    source cpi_env/bin/activate  # On macOS/Linux
    paco_env\Scripts\activate     # On Windows
    ```

2. **Install required dependencies**
    ```bash
    pip install -r requirements.txt
    pip install notebook
    ```
   
---

3. **Running the `main.ipynb` Notebook**
   To start the `main.ipynb` notebook directly, use the following command:
    ```bash
    jupyter notebook main.ipynb --port=8888
    ```
    Open a browser and go to `http://127.0.0.1:8888` to access the Jupyter environment and run the `main.ipynb` notebook.

---