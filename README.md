# README

## Data Science Fundamentals Exam - University of Udine (A.Y. 2023/24)

This project is part of the "Fondamenti di Scienza dei Dati" (Fundamentals of Data Science) exam at the University of Udine. The goal is to analyze economic indicators from the Federal Reserve Economic Data (FRED) to explore key economic trends.

## Requirements

The required Python dependencies are listed in the `files/requirements.txt` file.

To install them, run:

```bash
pip3 install -r files/requirements.txt
```

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

1. Ensure all dependencies are installed.
2. Configure your API key in the `.env` file.
3. Open the Jupyter Notebook and run the analysis.

---


