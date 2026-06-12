# Virtual Test-Bed for Geological Multi-Risk Assessment

## 📌 Project Overview
This project establishes a methodological framework to integrate natural process modeling with socioeconomic vulnerability data. The goal is to create a robust "Virtual Test-Bed" for geological risk mitigation, allowing for precise spatial analysis and data-driven decision-making.

## 🗺️ Data Integration & Processing
A comprehensive dataset was constructed focusing on the **Torto Basin**. The spatial domain was discretized into over **28,600 Slope Units (SU)**, ensuring a high-resolution topographical baseline.

Key integrations include:
* **Topographical Data:** Processing and routing of high-resolution DEMs.
* **Hydrological Data:** Integration of CHIRPS precipitation datasets.
* **Thermal Data:** Incorporation of SIAS sensor data for regional climate profiling.

## 🤖 Machine Learning & Explainable AI (XAI)
To move beyond traditional susceptibility mapping, the project employs **Random Forest** models to evaluate multi-risk scenarios. A critical component of this methodology is the use of Explainable AI. By implementing **SHAP (SHapley Additive exPlanations)**, the model's outputs are interpreted to understand exactly how each topographical and hydrological variable contributes to the localized risk level, ensuring transparency in the risk assessment process.

---
*Tools used: QGIS, Python, GeoPandas, scikit-learn, SHAP.*