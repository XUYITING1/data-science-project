# Hong Kong AQHI Analysis(2026.01)

## Problem / Research Question
How does air quality vary across different monitoring stations in Hong Kong, and what were the daily trends in January 2026?

## Dataset Source and Usage Permissions
The dataset is "Past Air Quality Health Index Records" downloaded from DATA.GOV.HK, provided by the Hong Kong Environmental Protection Department. The data is publicly available for public use.

## Methods and Tools Used
- **Language:** Python
- **Tools:** Jupyter Notebook, pandas (data cleaning and aggregation), matplotlib (visualization).
- **Cleaning:** Removed daily summary rows, forward-filled dates, handled missing values (`-`), stripped `*` annotations, and mapped `10+` to 10.

## Key Findings and Limitation
- **Key Findings:** Roadside stations (e.g., Causeway Bay, Central, Mong Kok) showed higher AQHI distributions compared to general stations. There were clear peak pollution days in mid-January and late January 2026.
- **Limitation:** The analysis only covers January 2026. It does not account for seasonal variations or meteorological factors that heavily influence air quality.

## Instructions for Running the Analysis
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `AQHI_HongKong_Analysis_2026.ipynb` in Jupyter Notebook.
4. Run all cells sequentially.
