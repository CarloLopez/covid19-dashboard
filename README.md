# COVID-19 Dashboard

## Project Overview
This project is a simple Python-based interactive data visualization tool designed for analyzing COVID-19 data. It uses Jupyter Notebooks to create dynamic, interactive graphs that illustrate various metrics such as tests conducted, confirmed cases, hospital admissions, and occupancy rates.

## Features
- **Interactive Data Selection:** Users can select different COVID-19 metrics to visualize.
- **API Data Fetching:** Incorporates real-time data fetching from the Public Health England API.
- **Interactive Graphs:** Utilizes `matplotlib` and `ipywidgets` for dynamic graph plotting.
- **Data Persistence:** Allows saving and loading of data via JSON files.
- **Refresh Functionality:** Includes a 'Refresh Data' button to update graphs with the latest available data.

## Installation
To set up this project, you will need a Python environment with Jupyter Notebook. The project relies on several Python libraries, including `pandas`, `numpy`, `matplotlib`, `ipywidgets`, and `uk_covid19`. You can install these dependencies using pip:
```bash
pip install pandas numpy matplotlib ipywidgets uk_covid19
```

## Usage
After installing the dependencies, launch Jupyter Notebook and open the project file. The interface includes dropdown menus and buttons to select data metrics and refresh the data. Graphs will update automatically based on your selections.

![image](https://github.com/CarloLopez/covid19-dashboard/assets/86852232/363c788a-dca1-41c7-8702-9728b9d3767e)
