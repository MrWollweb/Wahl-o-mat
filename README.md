# Analysis Based on Wahl-O-Mat Dataset

## Context

This repository contains an analysis based on the Wahl-O-Mat dataset. Wahl-O-Mat is a German election tool that helps voters compare their political views with party positions. The analysis includes various data processing and visualization techniques, such as PCA (Principal Component Analysis) and clustering methods.

## Dependencies

To run the script, make sure you have the following Python packages installed:

```bash
pip install pandas numpy plotly scikit-learn dash
```

## Data Source

The analysis is based on data from the file `data/2025.csv`. This file is read and processed in the script.

## Usage

Run the script in a Jupyter Notebook environment or start a Dash web application for interactive visualization of the results.

## Main Features

- **Data Processing**: Reading and transforming data into an analyzable format.
- **PCA Analysis**: Dimensionality reduction for better visualization.
- **Clustering**: Applying clustering methods to group parties based on their positions.
- **Interactive Visualization**: Displaying results using Plotly and Dash.

## License

This project is licensed under the MIT License. For more information, see the `LICENSE` file.
