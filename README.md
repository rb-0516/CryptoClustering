# Cryptocurrency Clustering Analysis

## Overview
This project performs clustering analysis on cryptocurrency market data using K-means clustering algorithm. The analysis is conducted both on the original scaled data and on dimensionality-reduced data using Principal Component Analysis (PCA). The goal is to identify patterns and groups in cryptocurrency price movements.

## Features
- Data preprocessing and standardization
- K-means clustering analysis
- Principal Component Analysis (PCA)
- Elbow curve optimization for cluster selection
- Interactive visualizations using hvPlot
- Comparative analysis between original and PCA-based clustering

## Dependencies
- Python
- Pandas
- scikit-learn
- hvPlot
- Other standard data science libraries

## Installation
1. Clone this repository
2. Download the required `crypto_market_data.csv` file
3. Ensure all required libraries are installed:
```python
pip install pandas numpy scikit-learn hvplot
```

## Project Structure
- `Crypto_Clustering.ipynb`: Main Jupyter notebook containing the analysis
- `crypto_market_data.csv`: Input data file containing cryptocurrency market information

## Analysis Workflow
1. **Data Preparation**
   - Load and inspect cryptocurrency market data
   - Scale data using StandardScaler
   - Create normalized DataFrame for analysis

2. **Initial Clustering Analysis**
   - Determine optimal k value using elbow method
   - Perform K-means clustering on scaled data
   - Visualize results with interactive scatter plots

3. **PCA Analysis**
   - Reduce data dimensions to three principal components
   - Analyze explained variance
   - Create PCA-transformed DataFrame

4. **PCA-Based Clustering**
   - Determine optimal k value for PCA data
   - Perform K-means clustering on PCA data
   - Compare clustering results with original analysis

## Visualizations
The project includes several interactive visualizations:
- Elbow curves for optimal k-value selection
- Scatter plots of cryptocurrency clusters
- PCA component analysis plots

## Usage
1. Open the Jupyter notebook `Crypto_Clustering.ipynb`
2. Run all cells in sequence
3. Analyze the generated visualizations and clustering results
4. Modify parameters as needed for different analysis scenarios

## Results
The analysis provides insights into:
- Natural groupings of cryptocurrencies based on price change patterns
- Effectiveness of dimensionality reduction in clustering analysis
- Comparative performance of different clustering approaches

## Data
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

## Contributing
This project is part of a data analytics assignment. While it's not open for direct contributions, feedback and suggestions are welcome.

## License
This project is created for educational purposes and follows standard academic guidelines.
