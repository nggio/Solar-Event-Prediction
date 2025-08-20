# DST Analysis

## Overview
This repository contains a Jupyter Notebook (`DST_analysis.ipynb`) for analyzing **Disturbance Storm Time (DST) index data** from the OMNI dataset. The notebook identifies geomagnetic storm events, classifies them by intensity, and outputs results in both tabular and graphical formats. This analysis was developed as part of **Climate 323: Final Project**.

## Features
- Loads and preprocesses **OMNI solar wind and DST index data** (`OMNI20032024.csv`).  
- Identifies geomagnetic storm events using DST thresholds.  
- Classifies storms into **moderate, intense, and extreme** based on **Palacios et al. (2018)** thresholds:  
  - **Moderate:** DST ≤ –75 nT  
  - **Intense:** DST ≤ –150 nT  
  - **Extreme:** DST ≤ –330 nT  
- Produces summary tables of events.  
- Exports identified storm events to a text file (`DST_events.txt`).  
- Generates **6 different plots** to visualize solar wind parameters, DST time series, and storm detection results.  

Install the following dependencies before running the notebook:

```bash
pip install numpy matplotlib python-dateutil tabulate
