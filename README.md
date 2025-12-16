## Title of the Project
An Interpretability-Driven AI Framework for Soil Fertility Prediction and Sustainable Crop Recommendation

## About
<!--Detailed Description about the project-->
The Intelligent Agriculture Assistant is a smart decision-support system designed to assist farmers, researchers, and agricultural officers in analyzing soil health, recommending suitable crops, and identifying optimal fertilizers. The system leverages advanced machine learning models and SHAP-based interpretability to provide transparent, data-driven suggestions that enhance agricultural productivity and sustainability.
The Intelligent Agriculture Assistant is developed to simplify and enhance agricultural decision-making by integrating machine learning with explainable AI. Farmers often struggle with determining soil fertility, choosing appropriate crops, or selecting optimal fertilizers due to limited technical knowledge or lack of access to expert agronomists.

This project addresses these challenges by providing:

A multi-model ML system (RandomForest + XGBoost) capable of predicting soil fertility, crop suitability, and fertilizer requirements.

A SHAP interpretability layer that explains why each prediction was made in clear, human-understandable terms.

A user-friendly Gradio interface enabling users to input soil and environmental parameters and instantly receive insights supported by visual charts and explanations.

The assistant aims to promote data-driven farming practices, improve yield quality, and increase accessibility to AI-powered agronomy tools.

## Features
- SHAP-based Explainable AI — Every prediction is accompanied by a feature-impact explanation.
- Multi-model Architecture — Separate ML models for soil fertility, crop recommendation, and fertilizer prediction.
- User-Friendly Interface — Built using Gradio with multi-page layout and graphical visualizations.
- High Scalability — Modular architecture allows new crops, soil types, or fertilizer databases to be added easily.
- Fast Inference — Optimized ensemble models ensure low prediction latency.
- Language Support — Output available in English and Tamil using a translation engine.
- Graphical Insights — Probability distribution graphs for each ML prediction.
- PDF Report Generation (Optional) — One-click export for results with explanations and plots.
## Requirements
<!--List the requirements of the project as shown below-->
### Operating System

64-bit Windows 10/11 or Ubuntu 18.04+

(Compatible with Google Colab and cloud platforms)

### Development Environment

Python 3.8 or later

### Machine Learning Frameworks

XGBoost – for gradient boosting-based prediction

RandomForest (Scikit-learn) – ensemble learning

### Explainability Framework

SHAP (SHapley Additive exPlanations) – core method for interpretability

### Image & Plotting Libraries

Matplotlib / Seaborn – for probability visualizations

PDFKit / ReportLab (optional) – for generating downloadable PDF reports

### Interface Framework

Gradio – modern, web-based UI with multipage layout

### Other Dependencies

pandas

numpy

imbalanced-learn (SMOTE)

deep-translator

IDE / Environment

Google Colab

## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="818" height="444" alt="image" src="https://github.com/user-attachments/assets/91510614-814f-4e64-a55c-fdab4a4d1a17" />



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Recommendation explanations
<img width="1865" height="647" alt="image" src="https://github.com/user-attachments/assets/05d2fb5f-47a1-409c-b6a7-ef56311bb09d" />



#### Output2 - Graphical explanations
<img width="1715" height="563" alt="image" src="https://github.com/user-attachments/assets/ecd9d01e-5f98-4b7b-9b82-8af24612768b" />


#### Accuracy
<img width="516" height="490" alt="image" src="https://github.com/user-attachments/assets/2097570e-f70a-4fee-a1c9-436002f6954c" />

<img width="468" height="197" alt="image" src="https://github.com/user-attachments/assets/cd4a440c-1b05-4f26-aa6a-60e8301cca7a" />




## Results and Impact
<!--Give the results and impact as shown below-->
The Intelligent Agriculture Assistant significantly improves agricultural decision-making by providing farmers and agronomists with:
Faster and more reliable soil fertility assessment
Clear crop recommendations based on scientific data
Fertilizer suggestions that reduce wastage and improve yield
Transparent AI explanations for trust-building and educational value
By integrating explainable AI, the system ensures users understand why a prediction was made, making it more trustworthy and suitable for real-world adoption.
This project demonstrates the practical application of Machine Learning and Explainable AI in the agricultural domain, contributing toward smart farming, precision agriculture, and sustainable resource management.

## Articles published / References
1. H. Chandra et al., "Explainable AI for Soil Fertility Prediction," IEEE Access, 2023, doi: 10.1109/ACCESS.2023.3311827.
2. A. Yenkikar, V. P. Mishra, M. Bali, and T. Ara, "An explainable AI-based hybrid machine learning model for interpretability and enhanced crop yield prediction," MethodsX, vol. 15, p. 103442, 2025.
3. Dong et al., "Enhancing soil organic carbon prediction by unraveling the role of crop residue coverage using interpretable machine learning," Geoderma, vol. 455, p. 117225, 2025.



