# Sensor Data Analysis

Simple pandas project.

## Installation

```bash
pip install -r requirements.txt
pip install openpyxl
```

## Usage

```bash
python process_sensor_data.py
```

## Files

- `sensor_data.csv`: Input data
- `process_sensor_data.py`: Analysis script
- `sensor_data_analyzed.csv`: Output results

- 'sensor_data.xlsx': input data
- 'sensor_data_analyzed.xlsx': Output Results

## What It Does

1. Loads CSV data (in the assingment it is xlxs)
2. Cleans missing values
3. Calculates averages by equipment
4. Flags high temperature readings (>50°C)
5. Exports results

## Requirements

- Python 3.7+
- pandas
