# COVID-19 Data Analysis using Python & Tableau

## Project Overview
This project provides a comprehensive analysis of COVID-19 data in India, focusing on infection trends, recovery rates, and vaccination progress across various states. By combining the data processing power of **Python** with the visualization capabilities of **Tableau**, this project transforms raw public health data into actionable insights.

## Features
- **Data Preprocessing:** Cleaning and structuring raw CSV data using `Pandas` and `NumPy`.
- **Exploratory Data Analysis (EDA):** Visualizing growth trends and mortality rates using `Matplotlib`, `Seaborn`, and `Plotly`.
- **Vaccination Analysis:** Tracking dose administration and identifying leading states in the vaccination drive.
- **Interactive Dashboards:** Exporting processed data to `Tableau` for high-level executive summaries and geospatial mapping.

## Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Tools:** Jupyter Notebook, Tableau
- **Environment:** Windows / Jupyter

## Data Processing Steps
1. **Cleaning:** Handling missing values and dropped unnecessary columns.
2. **Transformation:** Converting date strings to datetime objects and calculating Active Cases.
3. **Aggregations:** Grouping data by State/UT to find peak infection periods.
4. **Export:** Saving cleaned datasets (e.g., `covid_summary_for_tableau.csv`) for seamless integration with Tableau.

## Project Structure
- `covid_19 data analysis using python and tableau_v2.ipynb`: Main Python notebook containing the analysis logic.
- `covid_19_india.csv`: Dataset containing daily case counts.
- `covid_vaccine_statewise.csv`: Dataset tracking vaccination progress.
- `top_vaccinated_states.csv`: Processed output for specific visualizations.

## Key Insights
- Identification of states with the highest recovery rates.
- Correlation between vaccination rates and the decline in active cases.
- Time-series analysis of the pandemic's waves in India.

## How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`.
3. Run the Jupyter Notebook to generate the cleaned CSV files.
4. Open the generated CSVs in Tableau to explore the interactive dashboard.
