# House Price Exploratory Data Analysis

A beginner-friendly mini project that inspects, cleans, summarizes, and visualizes the supplied house sales CSV using Python.

## Project files
- `House_Price_EDA.ipynb` - executed notebook with code, explanations, tables, and charts
- `data/House_Price_data.csv` - original supplied CSV
- `outputs/cleaned_house_prices.csv` - positive-price records with derived analysis fields
- `outputs/House_Price_EDA_Report.pdf` - written report with findings, visualizations, and limitations

## Dataset overview
- 4,600 sales and 18 original columns
- Dates: 2014-05-02 to 2014-07-10
- 44 cities; 49 non-positive sale prices are excluded from price-based analysis
- The supplied file did not include source, license, or data dictionary metadata.

## Run the notebook
Open `House_Price_EDA.ipynb` in Jupyter Notebook or Google Colab and run all cells from the project root. In Colab, upload the notebook and the `data/House_Price_data.csv` file, preserving the `data/` path; the notebook writes the cleaned CSV to `outputs/`.

## Main takeaway
Sale prices are right-skewed and positively associated with living area. City medians differ, but these raw comparisons are not adjusted for home size, condition, or neighborhood. This is exploratory analysis only, not a prediction model or valuation tool.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter

## Source
`House_Price_data.csv`, supplied for this project. Original publisher and license were not identified in the provided file.
