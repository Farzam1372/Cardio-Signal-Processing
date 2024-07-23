# Cardio-Signal-Processing
----------------------
These are two different types of biosignals obtained simultaneously in our internal studies: 
1-PPG is the optical measurement of the pulse from the finger (using the camera).
2-ECG is the recording of the electrical activity of the heart. 

To analyze blood pressure or other metrics later, we need raw data. This data must be filtered to reduce noise and have the baseline of the signals detrended. This process ensures clear signals to build and use our model effectively.

relation between electrocardiogram (ECG) and photoplethysmogram (PPG) and infer the waveform of ECG via the PPG signals.

Methods In order to address this inverse problem, a transform is proposed to map the discrete cosine transform (DCT) coefficients of each PPG cycle to those of the corresponding ECG cycle. The resulting DCT coefficients of the ECG cycle are inversely transformed to obtain the reconstructed ECG waveform.

Results The proposed method is evaluated with the different morphologies of the PPG and ECG signals on three benchmark datasets with a variety of combinations of age, weight, and health conditions using different training modes. Experimental results show that the proposed method can achieve a high prediction accuracy greater than 0.92 in averaged correlation for each dataset when the model is trained subject-wise.

Conclusion With a signal processing and learning system that is designed synergistically, we are able to reconstruct ECG signal by exploiting the relation of these two types of cardiovascular measurement.

Significance The reconstruction capability of the proposed method may enable low-cost ECG screening for continuous and long-term monitoring. This work may open up a new research direction to transfer the understanding of clinical ECG knowledge base to build a knowledge base for PPG and data from wearable devices.
