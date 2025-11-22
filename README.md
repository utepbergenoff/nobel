# Nobel

Small project to collect, analyze, and visualize Nobel Prize data. Provides scripts and notebooks to explore laureates, categories, and historical trends.

## Features
- Import and normalize Nobel dataset (CSV/JSON)
- Basic analysis scripts and Jupyter notebooks
- Command-line utilities for filtering and exporting results

## Requirements
- Python 3.8+
- pip

Optional:
- JupyterLab or Jupyter Notebook for interactive notebooks

## Installation
1. Clone the repository:
    ```
    git clone <repo-url> nobel
    cd nobel
    ```
2. Create and activate a virtual environment:
    - Windows (PowerShell):
      ```
      python -m venv .venv
      .\.venv\Scripts\Activate.ps1
      ```
    - macOS / Linux:
      ```
      python3 -m venv .venv
      source .venv/bin/activate
      ```
3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

## Data
Place original data files in the `data/` directory. Expected filenames:
- `nobel_laureates.csv` or `nobel_laureates.json`

If no data is present, run the import script:
```
python scripts/import_data.py --input data/raw_input.csv --output data/nobel_laureates.csv
```

## Usage
- Run analysis script:
  ```
  python scripts/analyze.py --year 2020 --category physics
  ```
- Launch notebooks:
  ```
  jupyter lab notebooks/
  ```
- Export a filtered dataset:
  ```
  python scripts/export.py --category chemistry --output exports/chemistry_2020.csv
  ```

## Tests
Run unit tests:
```
pytest
```

## Contributing
- Fork the repository
- Create a feature branch
- Open a pull request with a clear description and tests for changes

## License
Specify a license in `LICENSE` (e.g., MIT).

## Contact
Open issues for bugs, feature requests, or questions.
