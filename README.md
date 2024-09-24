# Interactive Data Visualization App

A Streamlit web application that provides interactive data visualizations using Altair and Plotly. The app demonstrates scatter plots, line charts, area charts, pie charts, and histograms using various datasets.

## Table of Contents
1. [Altair Scatter Plot](#1-altair-scatter-plot)
2. [Interactive Charts](#2-interactive-charts)
   - [Line Chart](#21-line-chart)
   - [Area Chart](#22-area-chart)
3. [Data Visualization with Plotly](#3-data-visualisation-with-plotly)
   - [Displaying the dataset](#31-displaying-the-dataset)
   - [Pie Chart](#32-pie-chart)
   - [Pie Chart with Multiple Parameters](#33-pie-chart-with-multiple-parameters)
   - [Histogram](#34-histogram)
4. [Datasets](#datasets)
5. [Installation](#installation)
6. [Usage](#usage)

---

## 1. Altair Scatter Plot

The application uses **Altair** to display a scatter plot of random data. The plot includes:
- **X-Axis**: `a`
- **Y-Axis**: `b`
- **Size**: `c`
- **Tooltip**: Displays values for all the columns on hover.

## 2. Interactive Charts

### 2.1 Line Chart

- **Dataset**: `lang_data.csv`
- **Functionality**: The user can select multiple programming languages from the dataset to generate a line chart of their weekly popularity.

### 2.2 Area Chart

- **Dataset**: `lang_data.csv`
- **Functionality**: Displays an area chart based on the user's selection of languages from the line chart.

## 3. Data Visualization with Plotly

### 3.1 Displaying the dataset

The `tips.csv` dataset is displayed in the app, which includes details such as total bill, tip, day, and payment details.

### 3.2 Pie Chart

- **Dataset**: `tips.csv`
- **Functionality**: Displays a pie chart of the total bill grouped by day.

### 3.3 Pie Chart with Multiple Parameters

- **Dataset**: `tips.csv`
- **Functionality**: Adds opacity and custom color sequences to the pie chart to enhance visualization.

### 3.4 Histogram

- **Functionality**: Creates a histogram with three groups of random data and plots the distribution using **Plotly Figure Factory**.

## Datasets

1. **lang_data.csv**:
   Contains weekly popularity data of various programming languages.
   

2. **tips.csv**:
A dataset containing restaurant tips data, with columns such as total bill, tip amount, day, and other payment details.


## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SujalBochkar/freefaces-images.git
   cd freefaces-images
   ```

2. **Install the required dependencies**:
   You can install the required Python libraries by running:
   ```bash
   pip install -r requirements.txt
   ```
   The `requirements.txt` should include the following packages:
   ```
   streamlit
   requests
   beautifulsoup4
   ```
  
3. **Run the application**:
   To run the Streamlit app, use the command:
   ```bash
   streamlit run app.py
   ```
