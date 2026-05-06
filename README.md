# README

[![Python 3.13+](https://img.shields.io/badge/Python-3.13+-blue.svg)](https://www.python.org/downloads/)
[![uv](https://img.shields.io/badge/uv-enabled-ff6b35.svg)](https://docs.astral.sh/uv/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-f37726.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)](https://pandas.pydata.org/)

## Data Science Fundamentals Exam - University of Udine (A.Y. 2023/24)

This project is part of the "Fondamenti di Scienza dei Dati" (Fundamentals of Data Science) exam at the University of Udine. The goal is to analyze economic indicators from the Federal Reserve Economic Data (FRED) to explore key economic trends.

## Requirements

The required Python dependencies are listed in the `pyproject.toml` file.

To install them, run:

```bash
uv sync
```

This will create a virtual environment in `.venv` and install all dependencies.

## FRED API Configuration

To execute the notebook, you need an API key from FRED and must configure it in the repository.

### 1. Register on FRED

Visit the [FRED website](https://fred.stlouisfed.org/) and sign up to obtain an API key.

### 2. Create a `.env` File

In the root of the repository, create a `.env` file and add your API key:

```bash
API_KEY="your_api_key_here"
```

This will allow the notebook to fetch economic data from FRED seamlessly.

## Usage

1. Install uv [installation guide](https://docs.astral.sh/uv/getting-started/installation/)
2. Run `uv sync` to create the virtual environment and install dependencies
3. Activate the virtual environment: `source .venv/bin/activate` (on macOS/Linux) or `.venv\Scripts\activate` (on Windows)
4. Configure your API key in the `.env` file
5. Open the Jupyter Notebook and run the analysis

---


