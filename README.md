# Volatility-Ratios-in-Crypto-Currencies
"ATR / SMA Volatility Ratio visualization using Python and TA-Lib"
#############################################
# ATR / SMA Volatility Ratio Calculation
#############################################

## About This Project
This Python script calculates and visualizes the volatility ratio using the Average True Range (ATR) and Simple Moving Average (SMA). The script utilizes the TA-Lib library to compute the required indicators and generates a graph to display the results.

## Features
- Computes ATR and SMA indicators
- Calculates the volatility ratio (ATR / SMA)
- Applies a moving average to smooth the ratio
- Uses color coding to classify volatility levels (red, yellow, green)
- Visualizes the data with Matplotlib

## Requirements
To run this script, ensure you have the following dependencies installed:

```
pandas
numpy
matplotlib
TA-Lib
```

You can install the required libraries using pip:

```
pip install pandas numpy matplotlib TA-Lib
```

## How to Use
1. Clone or download the repository:
```
git clone https://github.com/YOUR_GITHUB_USERNAME/volatility-ratio.git
```

2. Navigate to the project folder:
```
cd volatility-ratio
```

3. Run the script:
```
python volatility_ratio.py
```

## Output
The script generates a plot displaying:
- **Orange line**: ATR/SMA ratio
- **Blue line**: Moving average of the ratio
- **Red dotted line**: High threshold (0.10)
- **Green dotted line**: Low threshold (0.03)
- **Gray line**: Zero reference line

## Customization
You can modify the following parameters in the script to adjust calculations:
- `atr_length = 14`  → ATR calculation period
- `sma_length = 14`  → SMA calculation period
- `ma_length = 14`   → Moving average period
- `high_threshold = 0.10` → Upper volatility threshold
- `low_threshold = 0.03`  → Lower volatility threshold

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Created by **Your Name** (GitHub: @Cagdas-Azakli)

For any questions or contributions, feel free to open an issue or submit a pull request!

