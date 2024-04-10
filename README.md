# SpaceX Launch Prediction

## Overview
This project is part of the [Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone?specialization=ibm-data-science) by IBM on Coursera. It focuses on using data science techniques to predict the outcomes of SpaceX Falcon 9 rocket launches through data collection, data wrangling, exploratory data analysis (EDA), interactive visual analytics, and predictive analysis.

<p align="center">
    <img src="README%20assests/intro_image.png" alt="Intro Image" style="width: 80%"/>
</p>


## Live Dashboard
Experience the interactive SpaceX Launch Prediction dashboard hosted live at [PythonAnywhere](http://timkong.pythonanywhere.com/). Explore the data-driven insights and visualizations in real-time.

<p align="center">
    <img src="README%20assests/Dash_app.png" alt="Dash app" style="width: 80%"/>
</p>

## Project Structure
- `data/`: Contains datasets used in the project.
- `Data Collection and Data Wrangling/`: Notebooks for data collection, web scraping, and data preparation.
- `Exploratory Data Analysis/`: Notebooks for performing EDA using Pandas, visualization libraries, and SQL.
- `Interactive Visual Analytics and Dashboard/`: Scripts and notebooks for creating interactive visualizations and dashboards with Plotly, Dash, and Folium.
- `Predictive Analysis/`: Notebook for developing and evaluating machine learning models to predict launch success.

## Datasets
- `spacex_launch_dash.csv`: Launch data for dashboard visualizations.
- `spacex_launch_geo.csv`: Geographical data for mapping launch sites.

## Quick Start
1. Clone this repository and navigate to the project's root directory:
   ```bash
   git clone https://github.com/TimKong21/SpaceX-Launch-Prediction.git
   cd SpaceX-Launch-Prediction
   ```
2. Set Up a Virtual Environment in the project directory:
   ```bash
   # For Windows
   python -m venv venv
   .\venv\Scripts\activate

   # For MacOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install Jupyter Notebook or JupyterLab to run `.ipynb` notebooks. If you don't have them installed, you can install JupyterLab with:
   ```bash
   pip install jupyterlab
   ```
4. Install required Python packages by running:
   ```bash
   pip install -r requirements.txt
   ```
5. Open the notebook(s) of interest with Jupyter by running:
   ```bash
   jupyter lab
   ```
6. To run the dashboard, navigate to the dashboard directory and then start the Dash app:
   ```bash
   cd ".\Interactive Visual Analytics and Dashboard\"
   python .\launch_record_analysis_dash_app.py
   ```