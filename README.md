# 🚀Anomaly-Detection-with-LSTM-Autoencoders

Ever wondered what it feels like to predict engine failures before they happen? Well, now you don’t have to just wonder — you can see it in action! 🛠️💥

This project uses an LSTM autoencoder to detect anomalies in engine sensor data from the NASA C-MAPSS FD001 dataset. Think of it as giving your engines a sixth sense — warning them (and you) before they break down.

## 🎯 Project Highlights

- Dataset: NASA FD001 — multiple engines with rich sensor telemetry.

- Model: LSTM Autoencoder trained to reconstruct “normal” engine behavior.

- Detection: Anomalies are flagged when reconstruction error exceeds a threshold.

- Visualization: See the rise of reconstruction errors and pinpoint anomalies on interactive and static plots.

## 🛠️ Features
- 🚦 Anomaly Detection: Automatically flags unusual engine behavior.

- 📊 Engine-specific analysis: Visualize reconstruction error per engine.

- 🔍 Sensor trends: Identify early signs of degradation across multiple sensors.


## 📈 How It Works

- Preprocessing: Scale sensor data and create sequences for LSTM input.

- Training: LSTM autoencoder learns to reconstruct normal engine cycles.

- Error Computation: Calculate reconstruction error per sequence.

- Thresholding: Identify sequences that deviate significantly from normal.

- Visualization: Highlight anomalies in plots — red dots for the suspicious ones! 🔴

## 🎨 Visualizations

- Reconstruction error curves for each engine

- Anomalies highlighted on cycles

- Sensor trends across time

- shaded degradation regions for easy spotting of early warning signs

## 🤓 Why This Is Cool

- Catch engine failures before they happen.

- Explore sensor data like a digital detective.

- Customize thresholds and visualizations to suit your needs.

## 🛠️ Next Steps / TODO

 [] Forecast sesnor readings to predict future anomalies
 
 [] Add interactive dashboards with Plotly

 [] Compare LSTM with other models (GRU, CNN Autoencoders)

## 💡 Fun Fact

Did you know? Early detection of anomalies in engines can save millions in maintenance costs and prevent catastrophic failures — all without breaking a sweat! 😎
