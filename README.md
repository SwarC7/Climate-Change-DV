# Climate Change Data Visualization Project

## Overview
This is a **Flask-based web application** designed to visualize the effects of climate change through various interactive charts and graphs. The application leverages **Plotly, D3.js, and Pandas** to analyze and display trends related to:
- **CO₂ Emissions per Country** (1800-2022)
- **Global Temperature Changes** (1901-2021)
- **Sea Level Rise Trends** (1880-2014)
- **Rainfall and Temperature Trends in India** (1901-2021)
- **Climate Change Disasters by Country** (1980-2022)
- **Per Capita Energy Consumption** (2022)

---

## Project Structure
```
├── app.py                     # Main Flask application
├── requirements.txt           # List of dependencies
├── templates/                 # HTML templates for the web app
│   ├── index.html             # Home page
│   ├── chart.html             # CO₂ emissions visualization
│   ├── choropleth.html        # Country-level emissions heatmap
│   ├── g.html                 # Sea level rise visualization
│   ├── h.html                 # Sunburst chart for energy sources
│   ├── i.html                 # Climate impact overview
│   ├── j.html                 # Temperature and Rainfall visualization
│   ├── k.html                 # Greenhouse gas emissions by state
│   ├── land.html              # Landing page with project introduction
│   ├── vis.html               # Page with all visualization options
├── static/                    # Static assets (CSS, images, data files)
│   ├── style.css              # Main stylesheet
│   ├── style1.css             # Additional styles for visualizations
│   ├── bg.jpg                 # Background image for UI
│   ├── earth.jpeg             # Climate impact image
│   ├── temp.csv               # Temperature dataset
│   ├── rainfall.csv           # Rainfall dataset
│   ├── total_disasters_per_country_cumulative.csv  # Disaster dataset
│   ├── output.csv             # Processed sea level data
│   ├── preprocessed_data.csv  # Cleaned emissions data
├── data/                      # (Optional) Additional datasets
│   ├── countries.geo.json     # GeoJSON for mapping
│   ├── GlobalTemperatures.csv # Historical temperature data
│   ├── seaice.csv             # Sea ice data
│   ├── data.zip               # Compressed dataset files
│   ├── dvp-1.zip              # Additional visualization data
├── README.md                  # Documentation file
```

---

## Installation and Setup

### **Prerequisites**
Ensure you have **Python 3.7+** installed on your system.

### **Step 1: Clone the repository**
```sh
$ git clone https://github.com/yourusername/climate-viz-project.git
$ cd climate-viz-project
```

### **Step 2: Install dependencies**
Use the `requirements.txt` file to install necessary packages.
```sh
$ pip install -r requirements.txt
```

### **Step 3: Run the Flask application**
```sh
$ python app.py
```
The application will start on `http://127.0.0.1:5000/`.

---

## Features and Functionality

### **1. Interactive Climate Data Visualizations**
- **CO₂ Emissions Over Time:** Displays emissions for selected countries over different years.
- **Global Temperature Trends:** Analyzes temperature rise over decades.
- **Sea Level Rise:** Tracks global sea level changes using historical records.
- **Climate Change Disasters:** Shows the impact of climate-related disasters worldwide.
- **Renewable vs Fossil Fuel Consumption:** Displays sunburst charts on energy usage.
- **Greenhouse Gas Emissions by State:** Visualizes emissions across different regions.

### **2. Dynamic Data Filtering**
Users can select different countries, years, or datasets to customize their analysis.

### **3. Choropleth Maps and Graphical Representation**
Includes **D3.js maps** and **Plotly charts** to provide visual insights.

---

## File Descriptions

### **Backend (Flask App)**
- `app.py`: Main Flask application that serves pages and handles API calls.
- `requirements.txt`: Lists required dependencies for the project.

### **Templates (HTML Frontend Pages)**
- `index.html`: Home page for navigation.
- `chart.html`: CO₂ emissions over time.
- `choropleth.html`: Choropleth map for emissions.
- `g.html`: Sea level rise visualization.
- `h.html`: Sunburst chart for energy sources.
- `j.html`: Temperature and rainfall visualization.
- `k.html`: Greenhouse gas emissions comparison.

### **Static Files (CSS, Images, and Data)**
- `style.css`, `style1.css`: Custom styles for the UI.
- `bg.jpg`, `earth.jpeg`: Background images used in the project.
- `temp.csv`, `rainfall.csv`, `total_disasters_per_country_cumulative.csv`: Climate-related datasets.
- `preprocessed_data.csv`: Cleaned and processed climate data for visualization.

---

## How to Use
1. Open `http://127.0.0.1:5000/` in a browser.
2. Select a visualization from the home page.
3. Use filters (year, country, region) to explore data interactively.
4. Analyze trends and patterns in climate change data.

---

## Future Improvements
- Adding **Machine Learning models** for climate trend prediction.
- Expanding the dataset to include **real-time data streaming**.




