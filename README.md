# ETS_STAT_MODEL
Introduction
The ETS statistical model is used for analyzing time series data to identify and forecast patterns. This project demonstrates the use of ETS models, including additive and multiplicative decomposition, simple moving average, and exponential weighted moving average, on the airline passengers dataset.

Installation
To run the script, you need to have Python installed along with the following libraries:

pandas
matplotlib
statsmodels
You can install these libraries using pip:

bash
Copy code
pip install pandas matplotlib statsmodels
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/ets_stat_model.git
Navigate to the repository directory:
bash
Copy code
cd ets_stat_model
Ensure you have the dataset airline-passengers.csv in the same directory as the script.
Run the script:
bash
Copy code
python ets_stat_model.py
Data
The script requires the airline-passengers.csv dataset, which contains monthly totals of international airline passengers from 1949 to 1960.

Features
Data Loading and Visualization: Load and visualize the time series data.
Seasonal Decomposition: Decompose the time series data into trend, seasonal, and residual components using additive and multiplicative models.
Simple Moving Average (SMA): Apply simple moving average with various window sizes to smooth the data.
Exponential Weighted Moving Average (EWMA): Apply exponential weighted moving average with various spans for smoothing and forecasting.
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.
