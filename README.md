## Uber Pickups Analysis in NYC

This Streamlit application analyzes Uber pickups data in New York City (NYC). It visualizes the number of pickups by hour and allows users to filter data based on the hour of the day.

### Data Source

The data used in this analysis is sourced from Uber's NYC pickups in September 2014. The dataset is publicly available and hosted on Amazon S3.

### Installation

To run this application, you need to have Python installed on your machine. Additionally, you need to install the following Python packages:

- Streamlit
- Pandas
- NumPy

You can install these dependencies using pip:

```
pip install streamlit pandas numpy
```

### Running the Application

To launch the Streamlit application, execute the following command in your terminal:

```
streamlit run <filename>.py
```

Replace `<filename>.py` with the name of the Python script containing the provided code.

### Functionality

- The application loads Uber pickups data from the provided URL.
- It displays the raw data upon request.
- It visualizes the number of pickups by hour using a histogram.
- Users can filter the data by hour using a slider and visualize the pickups on a map for the selected hour.

### Usage

- Upon running the application, it will load the data and display a text indicating the loading state.
- Once the data is loaded, it will show the raw data along with a checkbox to display it.
- Users can explore the number of pickups by hour using the histogram.
- By adjusting the slider, users can filter the pickups data by hour and view them on the map.

### About

This application is built using Streamlit, a Python library for creating interactive web applications. It provides a simple and efficient way to create data-driven applications directly from Python scripts.

