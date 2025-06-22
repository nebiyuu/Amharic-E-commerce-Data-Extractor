# Amharic-E-commerce-Data-Extractor

This project provides tools and scripts for extracting, cleaning, and analyzing Amharic e-commerce data, particularly from Telegram channels.

## Project Structure

- `data/`  
  Contains raw and processed datasets.
- `notebook/`  
  Jupyter notebooks for exploratory data analysis and labeling.
- `scripts/`  
  (Reserved for Python scripts and utilities.)
- `.github/workflows/`  
  GitHub Actions workflows for CI/CD.

## Notebooks

- `notebook/EDA_DATA.ipynb`: Exploratory data analysis and cleaning.
- `notebook/labling.ipynb`: Data labeling workflow.

## Requirements

Install dependencies with:

        ```pip install -r requirements.txt```



## Usage

1. Place your raw Telegram data in `data/telegram_data.csv`.
2. Run the notebooks in `notebook/` for data cleaning and analysis.
3. Cleaned data will be saved to `data/telegram_data_cleaned.csv`.

## Output

- Cleaned and processed data is stored in `data/Processed/`.

## License

MIT License .