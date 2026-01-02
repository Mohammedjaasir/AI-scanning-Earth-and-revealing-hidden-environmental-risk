## AI scanning Earth and revealing hidden environmental risk

This repository contains an end-to-end Earth Intelligence system that learns normal environmental behavior directly from multi-sensor satellite data and automatically detects hidden environmental anomalies — without using labeled data.

Instead of classifying land or generating static maps, the system models normality and highlights deviations using unsupervised deep learning.
---

 ![5b339e93-80fb-4354-8497-9723e73d71e6](https://github.com/user-attachments/assets/cf67c347-2b7f-49c7-8a97-42ffbe30ac9f)

 ---
![35240fc7-84e4-4848-875d-938d04a2a245](https://github.com/user-attachments/assets/e319a79c-4c91-45f8-b99a-c2302b94fd55)
---
![3425d169-4ec3-43c2-8b67-efc9aa91b7e9](https://github.com/user-attachments/assets/419a148c-33c5-4969-9bee-278c5dde9de5)

---




 

 🧠 Core Idea

Traditional Earth observation answers:

“What is present at this location?”

This project answers a deeper question:

“Is this location behaving normally compared to its learned environmental pattern?”

The system learns long-term environmental behavior and flags subtle stress signals that are often invisible to human interpretation.

---

🛰️ Data Sources

Multi-sensor satellite and climate datasets are used to capture complementary Earth signals:

Sentinel-2 — Optical imagery (vegetation & surface patterns)

Sentinel-1 — Radar imagery (structural & ground disturbance)

SMAP — Soil moisture (subsurface stress indicator)

ERA5 — Climate & rainfall signals

All large-scale preprocessing is performed using Google Earth Engine.

---

Satellite Data (Multi-Year, Multi-Sensor)
            ↓
   Feature Engineering & Fusion (GEE)
            ↓
   Learned Environmental Normality
            ↓
   Unsupervised Autoencoder
            ↓
   Reconstruction Error
            ↓
   Environmental Anomaly & Risk Maps

  ---

🤖 Methodology

Phase 1 — Statistical Baseline

NDVI time-series analysis

Z-score based anomaly detection

Establishes a baseline understanding of normal behavior

Phase 2 — AI-Based Intelligence

Multi-sensor feature stacking

Unsupervised autoencoder trained on normal patterns

Anomalies detected via reconstruction error

Phase 3 — Explainability & Risk Mapping

Feature-wise contribution analysis

Normalized risk maps

Decision-ready outputs for monitoring and planning

---

🧪 Tech Stack

Google Earth Engine — satellite data processing

Python — core analysis

TensorFlow / Keras — autoencoder model

NumPy, Scikit-learn — data processing

Rasterio — geospatial raster handling

Google Colab — model training & experimentation

---

📊 Outputs

Environmental anomaly maps

Normalized risk zones (low / medium / high)

Feature contribution analysis (explainable AI)

LinkedIn-ready visualizations & videos

---

🎯 Applications

Environmental stress monitoring

Climate risk analysis

Urban expansion & land disturbance detection

Early warning systems

Research & policy decision support

---

🔍 Why This Project Is Different

❌ No land-use classification

❌ No labeled training data

❌ No manual thresholds

✅ Self-learning
✅ Unsupervised
✅ Multi-sensor
✅ Explainable
✅ Scalable

This approach aligns with how foundation models and modern Earth intelligence systems are designed.

---

🚀 Future Work

Temporal forecasting of environmental collapse

District-level risk ranking

Real-time monitoring pipelines

Integration with decision dashboards

---

📌 Author

Built by: Mohammed Jaasir 
Focus: AI • Earth Intelligence • Unsupervised Learning


