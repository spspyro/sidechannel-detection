# sidechannel-detection
Project artifacts for Side-channel detection using LSTM/Transformer model time-series forecasting

Collected data using Intel PCM to obtain variety of performance counters for feature selection.
Included dataset (after extracting data2.zip) uses L1-icache-loads and L1-icache-load-misses, but can be switched out for others.

Implements data pre-processing steps along with an LSTM model for baseline comparison, as well as exploratory implementations of transformer models

Anomaly detection method inspired by FortuneTeller model (https://arxiv.org/pdf/1907.03651.pdf)

Edit to necessary file paths to run notebook
