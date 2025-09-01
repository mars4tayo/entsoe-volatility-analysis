

---


https://github.com/user-attachments/assets/3d62a7f3-df07-4925-a2fc-77d58c6a7a51


# ENTSOE Electricity Price Volatility Analysis

This repository contains a Python-based analysis of electricity price volatility across European bidding zones using ENTSO-E day-ahead market data from 2016 to 2024. The project processes raw data, calculates daily volatility metrics, and visualizes seasonal trends and regional disparities.

## Overview

The script downloads and extracts ENTSO-E data, combines CSV files, filters for the 2016-2024 period, and computes daily price volatility (standard deviation of hourly prices). It generates plots including:
- Daily price volatility over time.
- Monthly volatility distribution to highlight seasonal patterns.
- Top 5 and bottom 5 most/least volatile bidding zones.

The analysis reveals insights into how renewable energy growth and market events influence volatility, with a focus on aggregated European trends.

## Author
- Omotayo Alexander Olanusi
- GitHub: [github.com/mars4tayo](https://github.com/mars4tayo)

## Requirements
- Python 3.8+
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `requests`
  - `zipfile`

Install dependencies using:
```bash
pip install -r requirements.txt
```

(*Note: Create a `requirements.txt` file with the listed libraries if not already present.*)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/mars4tayo/entsoe-volatility-analysis.git
   cd entsoe-volatility-analysis
   ```
2. Configure the `CONFIG` dictionary in the script with your local paths (e.g., `base_folder`, `download_path`, etc.) under `C:\\Users\\YourUsername\\...`.
3. Ensure you have write permissions for the specified directories.

## Usage
Run the script to perform the analysis and generate plots:
```bash
python main.py
```
- Data will be downloaded and extracted automatically.
- Output plots will be saved in the `output` directory (e.g., `volatility_trend.png`, `seasonality.png`).

## Data Source
The script uses ENTSO-E day-ahead price data from a ZIP archive (URL placeholder removed for privacy; update with the correct source if publicly available).

## Future Plans
A detailed write-up will be added to Medium in the future, expanding on the analysis and insights. Contributions and suggestions are welcome!

## License
Copyright (c) 2025 Omotayo Alexander Olanusi. All rights reserved. (Add an appropriate open-source license, e.g., MIT, if desired.)

## Contact
For questions or collaboration, reach out via GitHub or email (if provided).

---

