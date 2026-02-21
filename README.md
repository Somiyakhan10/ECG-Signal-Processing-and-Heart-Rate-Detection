# ECG Signal Processing and Heart Rate Detection

## Overview
This project processes ECG (Electrocardiogram) signals to detect R-peaks, calculate heart rate, identify abnormal spikes, and highlight sustained abnormal activity. Users can upload their own ECG datasets in CSV format. The results are visualized using plots for easy interpretation.

## Features
- Upload ECG CSV dataset
- Filter noise from ECG signals
- Detect heartbeats (R-peaks)
- Calculate average heart rate
- Identify abnormal spikes
- Highlight sustained abnormal regions (>5 seconds)
- Visualize results with clear plotting

## Requirements
- Python 3.x
- Libraries: numpy, pandas, matplotlib, scipy, biosppy, peakutils
- Recommended: Google Colab or Jupyter Notebook

## Dataset Format
- CSV file with a single column of ECG values
- Example:

| ECG Signal |
|------------|
| 0.01       |
| 0.03       |
| 0.02       |
| ...        |

- Set the correct sampling frequency (`fs`) according to your dataset

## Installation
```bash
pip install numpy pandas matplotlib scipy biosppy peakutils
