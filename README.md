Luxury Homes

Objective: Understand how different parameters afftect property mortgage based on a number of purposes

Compatibility Issue:
1. Plotly is unable to be rendered if running with JupyterLab (it is a known issue, see: https://github.com/plotly/plotly_express/issues/17). 
	However, the Dash app can still be rendered.
	Suggestion: Use Jupyter Notebook in Docker or local machine for running the scripts.

Program: 
1. Anaconda Navigator 1.9.12
2. Python version 3.6.4
3. Jupyter Notebook 5.4.0

Software Packages:
1. pandas==0.25.3
2. numpy==1.14.2
3. plotly==4.8.1
4. seaborn==0.8.1
5. matplotlib==2.2.2
6. folium==0.11.0
7. dash==1.4.1

Installation:
pip install package 
or 
conda install -c conda-forge package 

Data:
1. Loan data: "LuxuryLoanPortfolio.csv"
2. States data: "zip_codes_states.csv"
3. Neighborhood data: "nyc_neighboor.csv"
4. Geo data: "nyc_zip_code_tabulation_areas_polygons.geojson"
Avaliable on: https://github.com/YJawata/Loan_Analysis_NYC

How to Run the Notebook:
1. Install required packages 
2. Run the scripts (the Dash app script is integrated to the notebook)
3. Open browser: http://localhost:8050/ to open the web apps
Note: a map will be created when the script is executed.
