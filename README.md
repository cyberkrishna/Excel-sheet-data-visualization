# Excel Analyzer :1234:

A simple and interactive web application built with [Streamlit](https://streamlit.io/) and [Plotly](https://plotly.com/python/) that allows users to upload an Excel file, analyze the data, and visualize it using various chart types.

## Features

- **File Upload**: Upload Excel files (`.xlsx`, `.xls`) for analysis.
- **Automatic Date Column Detection**: Automatically detects date columns in the uploaded data for easy filtering.
- **Data Filtering**: Filter data based on a specified date range.
- **Data Visualization**: Generate interactive charts, including:
  - Bar Chart
  - Line Chart
  - Pie Chart
  - Scatter Plot
  - Box Plot
- **Summary Statistics**: Display summary statistics for selected numerical columns.
- **Interactive Data Table**: View and explore the uploaded data.

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/excel-analyzer.git
    cd excel-analyzer
    ```

2. **Create and activate a virtual environment (optional but recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

    The app should automatically open in your default web browser. If it doesn't, navigate to [http://localhost:8501](http://localhost:8501) manually.

## Usage

1. **Upload an Excel File:** Use the file uploader to select and upload your Excel file.

2. **Preview the Data:** After uploading, a preview of the data will be displayed.

3. **Select Time Period:** Use the date range selector to filter the data by a specific time period.

4. **Choose a Chart Type:** Select the type of chart you want to generate (Bar, Line, Pie, Scatter, Box).

5. **Select Columns:** Choose the category column for the X-axis and the numerical data columns for the Y-axis.

6. **Generate Chart:** Click on the chart type to generate and display the chart.

7. **View Summary Statistics:** (Optional) Check the sidebar to display summary statistics for the selected data columns.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/) - Framework for building the web application.
- [Plotly](https://plotly.com/python/) - Library for creating interactive plots.
