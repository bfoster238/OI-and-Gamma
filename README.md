# Options Gamma and Open Interest Visualizer

This Python project calculates and visualizes the net gamma exposure and open interest for options data. The tool uses the Black-Scholes model to compute gamma exposure and displays the results along with open interest data for a selected stock and expiration date. You will need a FRED API key to run this code. 

## Features

- **Net Gamma Exposure Calculation**: Computes gamma exposure using the Black-Scholes model and aggregates by strike price.
- **Open Interest Visualization**: Displays the open interest for both calls and puts by strike.
- **Interactive Widgets**: Allows users to input stock tickers and select expiration dates through a dropdown.
- **FRED API Integration**: Fetches risk-free rate data (3-month Treasury Bill) from FRED.
- **Plotly Charts**: Visualizes net gamma exposure and open interest with dynamic charts.
