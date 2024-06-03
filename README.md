## Adidas Interactive Sales Dashboard

This Streamlit application provides an interactive dashboard for visualizing Adidas sales data. The dashboard includes various charts and tables for detailed analysis.

### Features

- **Total Sales by Retailer**: Bar chart visualization.
- **Monthly Sales Over Time**: Line chart visualization.
- **Sales and Units Sold by State**: Combined bar and line chart.
- **Sales by Region and City**: Treemap visualization.
- **Downloadable Data**: Download options for all the summarized data.

### Installation

#### Prerequisites

- Python 3.6 or higher
- Required libraries listed in `requirements.txt`

#### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/app.git
   cd app
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

### Usage

1. **Start the Application**: Run the Streamlit application as described above.
2. **Interact with the Dashboard**: Explore various charts and tables for detailed sales analysis.
3. **Download Data**: Use the download buttons to get the summarized data in CSV format.


#### Key Components:

- **Data Loading**: Reads sales data from an Excel file.
- **Charts and Visualizations**: Uses Plotly for creating interactive charts.
- **Download Options**: Allows users to download summarized data as CSV files.

---

## Sample SuperStore EDA

This Streamlit application provides exploratory data analysis (EDA) for the Sample SuperStore dataset. It includes various visualizations and filters for in-depth analysis.

### Features

- **Date Filters**: Filter data by order date range.
- **Region, State, and City Filters**: Interactive filtering options.
- **Category-wise Sales**: Bar chart visualization.
- **Region-wise Sales**: Pie chart visualization.
- **Time Series Analysis**: Line chart for sales over time.
- **Hierarchical View**: Treemap visualization by region, category, and sub-category.
- **Segment-wise and Category-wise Sales**: Pie chart visualizations.
- **Scatter Plot**: Relationship between sales and profit.

### Installation

#### Prerequisites

- Python 3.6 or higher
- Required libraries listed in `requirements.txt`

#### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Dashboard.git
   cd Dashboard
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

### Usage

1. **Start the Application**: Run the Streamlit application as described above.
2. **Upload Dataset**: Upload the `Superstore.csv` file or any other compatible dataset.
3. **Explore the Data**: Use the filters and visualizations to analyze the dataset.
4. **Download Data**: Use the download buttons to get the summarized data in CSV format.


#### Key Components:

- **File Upload**: Allows users to upload CSV or Excel files.
- **Date and Region Filters**: Filters data based on selected date range and region.
- **Charts and Visualizations**: Uses Plotly for creating interactive charts.
- **Download Options**: Allows users to download summarized data as CSV files.

