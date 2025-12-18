🚨 Robust Real-Time Network Traffic Anomaly Detection using LSTM

This project implements a **robust, low-latency, real-time network traffic anomaly detection system** using **Long Short-Term Memory (LSTM)** neural networks.
The system learns normal network behavior from sequential traffic data and detects anomalies based on reconstruction/prediction errors.

🔗 **Live Demo:**
👉 [https://v0-network-traffic-anomaly-detectio.vercel.app/](https://v0-network-traffic-anomaly-detectio.vercel.app/)

---

## ✨ Features

* LSTM-based temporal modeling of network traffic
* Real-time and low-latency anomaly detection
* Unsupervised / semi-supervised training support
* Streaming-ready architecture
* Easily extendable to Transformers, GNNs, and Federated Learning
* Research-paper–aligned implementation

---

## 📁 Project Structure

```
lstm-network-anomaly-detection/
│
├── data/               # Raw and processed datasets
├── preprocessing/      # Feature extraction and sequence building
├── models/             # LSTM model, training, evaluation
├── streaming/          # Real-time detection modules
├── configs/            # Configuration files
├── experiments/        # Results and logs
├── requirements.txt
└── README.md
```

---

## ⬇️ Download & Run (ZIP Method)

### 🔹 Step 1: Download ZIP

1. Click **Code** → **Download ZIP**
2. Extract the ZIP file
3. Open a terminal in the extracted folder

---

## 🛠️ Environment Setup

### 🔹 Step 2: Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows
```

---

### 🔹 Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📊 Datasets Supported

You may use any of the following datasets:

* **NSL-KDD**
* **CICIDS2017**
* **UNSW-NB15**

Place datasets inside:

```
data/raw/
```

---

## 🧠 Train the LSTM Model

```bash
python models/train.py
```

This trains the LSTM using normal traffic sequences and saves the model locally.

---

## ⚡ Run Real-Time Anomaly Detection

```bash
python streaming/real_time_detector.py
```

The detector computes reconstruction error and flags anomalies in real time.

---

## 🌐 Live Web Interface

A live visualization and demonstration of the anomaly detection pipeline is available here:

🔗 **Live Demo:**
[https://v0-network-traffic-anomaly-detectio.vercel.app/](https://v0-network-traffic-anomaly-detectio.vercel.app/)

> The web interface showcases anomaly detection behavior and system workflow for demonstration and presentation purposes.

---

## 🔬 Research Context

This implementation supports research in:

* Network intrusion detection systems (IDS)
* Time-series anomaly detection
* Deep learning for cybersecurity
* Real-time and streaming analytics

The architecture aligns with IEEE-style research contributions and can be extended for experimental evaluation.

---

## 🚀 Future Extensions

* Transformer-based anomaly detection
* Graph Neural Networks (GNNs) for flow relationships
* Online and continual learning
* Federated intrusion detection
* Adversarial robustness enhancements
* Edge and IoT deployment optimizations

---

## 📜 License

MIT License

© 2025 Kaushik Pinninti

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome.
Feel free to fork this repository and submit pull requests.

---

## 📬 Contact

For research collaboration or questions, please open an issue in the repository.

**Author:** Kaushik Pinninti

---

