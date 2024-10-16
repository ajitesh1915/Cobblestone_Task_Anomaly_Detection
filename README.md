# Anomaly Detection with Isolation Forest

This project implements an anomaly detection algorithm using the Isolation Forest method. The code generates a synthetic data stream with seasonal patterns and noise, identifies anomalies, and visualizes the results.

## Overview

The Isolation Forest algorithm works by isolating observations in a dataset. It constructs a set of trees (the forest) from random subsets of the data and measures the path lengths from the root to the leaves. Shorter path lengths indicate anomalies, as they are easier to isolate.

## Features

- **Synthetic Data Generation:** Generates a data stream with seasonal sinusoidal patterns and random noise, including occasional anomalies.
- **Isolation Forest Implementation:** Fits an Isolation Forest model to the generated data.
- **Anomaly Detection:** Identifies anomalies based on path lengths in the Isolation Forest.
- **Visualization:** Plots the data stream before and after anomaly detection.

## Requirements

This project requires the following Python libraries:

- `numpy`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install numpy matplotlib
