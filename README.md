# TimeSeriesAnomalyDetection

## Problem Statement
Use real-world Electrocardiogram (ECG) data to detect anomalies in a patient heartbeat.
## Proposed Solution
We will build an LSTM Autoencoder, train it on a set of normal heartbeats and classify unseen examples as normal or anomalies. We will use real-world ECG data from a single patient with heart disease to detect abnormal heartbeats.
## Data
The dataset contains 5,000 Time Series examples (obtained with ECG) with 140 timesteps. Each sequence corresponds to a single heartbeat from a single patient with congestive heart failure. <br/>
An electrocardiogram (ECG or EKG) is a test that checks how your heart is functioning by measuring the electrical activity of the heart. With each heartbeat, an electrical impulse (or wave) travels through your heart. This wave causes the muscle to squeeze and pump blood from the heart. <br/>
We have 5 types of heartbeats (classes): <br/>
• Normal (N) <br/>
• R-on-T Premature Ventricular Contraction (R-on-T PVC) <br/>
• Premature Ventricular Contraction (PVC) <br/>
• Supra-ventricular Premature or Ectopic Beat (SP or EB) <br/>
• Unclassified Beat (UB). <br/>
Assuming a healthy heart and a typical rate of 70 to 75 beats per minute, each cardiac cycle, or heartbeat, takes about 0.8 seconds to complete the cycle. Frequency: 60–100 per minute (Humans) Duration: 0.6–1 second (Humans)
