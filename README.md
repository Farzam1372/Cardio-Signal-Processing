# Cardio-Signal-Processing
----------------------
These are two different types of biosignals obtained simultaneously in our internal studies: 
1-PPG is the optical measurement of the pulse from the finger (using the camera).
2-ECG is the recording of the electrical activity of the heart. 

To analyze blood pressure or other metrics later, we need raw data. This data must be filtered to reduce noise and have the baseline of the signals detrended. This process ensures clear signals to build and use our model effectively.

# Synchronization and Evaluation of ECG and PPG Signals
Overview
This project aims to synchronize ECG (Electrocardiogram) and PPG (Photoplethysmogram) signals, evaluate the quality of the PPG signals, and rank them based on their signal quality. The synchronization process ensures that the signals are aligned for accurate comparison, and the evaluation metrics help in identifying the best quality PPG signal.

# Project Structure
## 1.Preprocessing of ECG and PPG Signals
- Apply filtering to remove noise and artifacts.
- Use appropriate cutoff frequencies for both ECG and PPG signals.

## 2.Peak Detection
- Detect peaks in the filtered signals.
- Peaks indicate heartbeats and are used for signal alignment.

## 3.Signal Synchronization
- Align ECG and PPG signals from their starting points.
- Resample ECG signals to match the length of PPG signals.

## 4.Evaluation of PPG Signals
- Calculate Signal-to-Noise Ratio (SNR).
- Assess peak prominence and variability.
- Combine these metrics to rank the signals.

## 5.Visualization
- Plot synchronized signals.
- Focus on specific ranges to compare signal quality.
