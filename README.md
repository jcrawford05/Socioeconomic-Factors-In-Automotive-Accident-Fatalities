# Socioeconomic Factors in Automotive Accident Fatalities

## Project Summary

This project analyzes the relationship between socioeconomic conditions and fatal motor vehicle accidents across U.S. states. Using publicly available data, the analysis explores how factors such as income, education, employment, and insurance coverage correlate with traffic fatality rates.

The full analysis is presented as an interactive, narrative-driven report hosted via GitHub Pages, with all underlying code available in a Jupyter Notebook.

## Live Report

🔗 **Interactive Analysis (GitHub Pages):**  
https://jcrawford05.github.io/Socioeconomic-Factors-In-Automotive-Accident-Fatalities/

The GitHub Pages site contains the complete notebook rendered as HTML, including all visualizations, commentary, and results.

## Repository Contents

- `Socioeconomic_Factors_In_Automotive_Accident_Fatalities.ipynb`  
  Source Jupyter Notebook containing all code, analysis, and visualizations

- Exported HTML file (generated via `nbconvert`)  
  Deployed for a GitHub Page

- `README.md`  
  Project overview and documentation

## Research Focus

**Primary question:**  
How do socioeconomic factors relate to state-level automotive accident fatality rates in the United States?

The project emphasizes exploratory analysis and interpretation rather than predictive modeling, with a focus on understanding real-world patterns in public safety data.

## Data Sources

The analysis combines multiple state-level datasets, including:

- U.S. traffic fatality and driving behavior statistics  
- Socioeconomic indicators such as income, education, employment, and insurance coverage  

All data preprocessing, cleaning, and merging steps are documented directly in the notebook.

## Methodology

The project follows a clear analytical pipeline:

1. Data ingestion and inspection  
2. Cleaning and normalization across datasets  
3. Exploratory data analysis using statistical summaries and visualizations  
4. Interpretation of observed trends and relationships  

The goal is to present findings in a clear, reproducible, and interpretable manner.

## Key Takeaways

- Socioeconomic conditions show meaningful variation across states and appear to correlate with fatal accident rates  
- Higher economic stability is often associated with lower fatality rates, though relationships are not uniform  
- Results highlight correlation rather than causation and motivate deeper investigation

## Tools and Technologies

- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- nbconvert  
- GitHub Pages

## Reproducibility

To reproduce the analysis locally:

1. Clone the repository  
2. Install required Python dependencies  
3. Open the `.ipynb` file in Jupyter (I used Google's CoLab for everything) 
4. Run all cells from top to bottom  

The HTML report was generated directly from the notebook using `nbconvert`.

## Notes

- The analysis is observational and does not establish causality  
- State-level aggregation may obscure local trends  
- Public datasets may contain reporting inconsistencies

