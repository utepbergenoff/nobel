# Nobel Prize Analysis: Global Patterns in Scientific Recognition (1901-2023)

## Overview
Comprehensive analysis of 122 years of Nobel Prize data exploring demographic, geographic, and temporal patterns in scientific achievement.

## Requirements
- Python 3.8+
- Jupyter Notebook or JupyterLab

## Installation
```bash
# Create virtual environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1  # Windows
source .venv/bin/activate      # macOS/Linux

# Install dependencies
pip install pandas seaborn matplotlib numpy jupyter
```

## Usage
```bash
jupyter notebook workspace/notebook.ipynb
```

## Data
- Location: `data/nobel.csv`
- Source: Nobel Prize API
- Time Period: 1901-2023

## Analysis Includes
1. Demographic patterns (gender & birth country)
2. US dominance across decades
3. Gender equity trends
4. First female laureate analysis
5. Multiple Nobel Prize winners

## Project Structure
```
nobel/
├── README.md
├── workspace/
│   └── notebook.ipynb
└── data/
    └── nobel.csv
```