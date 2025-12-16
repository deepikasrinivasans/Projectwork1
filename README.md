
#  NeuroFirewall – AI-Powered Real-Time Brainwave Threat Detection

### **An Intelligent EEG-based Cyber Defense Simulation System**

NeuroFirewall is an **AI-driven real-time EEG (brainwave) analysis system** built using **TensorFlow, Streamlit, and dynamic neural visualizations**.
It simulates brain activity, classifies emotional/threat levels using a neural network model, and provides **live visualization, adaptive background transitions, sound alerts, and threat logs**.

##  **Features**

###  **1. AI EEG Emotion/Threat Classification**

* ML model trained on *emotions.csv*
* Predicts 3 states:

  * **Safe**
  * **Alert**
  * **Harmful**

###  **2. Real-Time EEG Signal Simulation**

* Generates synthetic EEG data based on noise scaling
* Streams dynamically to the UI at runtime

###  **3. Neural Activity Heatmap Visualization**

* Animated brain activity using Matplotlib
* Color-coded activation intensity maps

###  **4. Live Adaptive Background System**

* Background color changes based on threat level:

  * 🟩 Safe → Green
  * 🟧 Alert → Orange
  * 🟥 Harmful → Red
* Auto-clears previous background styles to avoid stacking

###  **5. Audio Feedback Engine**

* Uses **pygame** to generate sound tones for each threat state

###  **6. Real-Time Threat Logging**

* Live timestamped entries of:

  * State (Safe/Alert/Harmful)
