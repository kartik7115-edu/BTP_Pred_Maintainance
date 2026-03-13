# Predictive Maintenance using LSTM Autoencoder

A machine learning system for **predictive maintenance, anomaly detection, and Remaining Useful Life (RUL) prediction** for industrial machines using time-series sensor data.

This project uses **LSTM Autoencoder networks** to learn normal behavior patterns of machine sensors and detect anomalies that may indicate potential machine failures.

---

## Project Overview

Modern industries rely on predictive maintenance to reduce downtime and avoid catastrophic machine failures. Traditional maintenance strategies like reactive or scheduled maintenance are inefficient.

This project implements a **data-driven predictive maintenance system** capable of:

• Detecting abnormal machine behavior  
• Predicting machine failure patterns  
• Estimating Remaining Useful Life (RUL)  

The model is trained using **sensor time-series data** from machine bearings and identifies anomalies using reconstruction error from an LSTM Autoencoder.


## Key Features

- Time-series sensor data processing
- LSTM Autoencoder architecture
- Anomaly detection using reconstruction loss
- Remaining Useful Life (RUL) estimation
- Data preprocessing and feature scaling
- Sliding window sequence generation
- Visualization of anomalies and predictions

---

## Dataset

The project uses the **IMS Bearing Dataset** which contains vibration sensor data from industrial bearings.

Dataset includes:

- Vibration signals
- Sensor measurements
- Time series machine condition data

Dataset file used in this repository:
[merged_Dataset_BearingTest_2.csv](https://github.com/user-attachments/files/25959876/merged_Dataset_BearingTest_2.csv)


Reference:

IMS Bearing Dataset – University of Cincinnati

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Sliding Window Sequence Creation
4. Feature Normalization
5. LSTM Autoencoder Model Training
6. Reconstruction Error Calculation
7. Anomaly Detection
8. Remaining Useful Life Estimation
9. Visualization of Results

---

## Model Architecture

The core model used in this project is an **LSTM Autoencoder** consisting of:

Encoder
- LSTM Layers
- Latent Representation

Decoder
- LSTM Layers
- Reconstruction of Input Sequence

Anomalies are detected when the **reconstruction error exceeds a predefined threshold**.

---

## Tech Stack

Programming Language

- Python

Libraries & Frameworks

- NumPy
- Pandas
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

Development Environment

- Jupyter Notebook

---

## Repository Structure
BTP_Pred_Maintainance
│
├── 1st_test
│
├── 2nd_test
│
├── 3rd_test
│
├── notebooks
│
├── merged_Dataset_BearingTest_2.csv
│
├── Readme Document for IMS Bearing Data.pdf
│
└── README.md


---

## Installation

Clone the repository

Install required libraries
pip install numpy pandas scikit-learn tensorflow matplotlib seaborn

Run the notebook

---

## Results

The model successfully:

- Detects abnormal machine behavior
- Identifies early signs of failure
- Estimates machine degradation
- Predicts remaining useful life

Visualizations include:

- Reconstruction error plots
- Anomaly detection graphs
- Sensor behavior trends

---

## Applications

Predictive maintenance systems like this can be applied in:

- Manufacturing plants
- Power plants
- Aerospace systems
- Automotive industry
- Smart factories (Industry 4.0)

---

## Future Improvements

- Real-time anomaly detection
- Deployment using Flask / FastAPI
- Integration with IoT sensor streams
- Edge deployment
- Dashboard visualization

---

## Author

Sujai Shukla

Mechanical Engineering  
Machine Learning & AI Enthusiast

---

## License

This project is for academic and research purposes.
