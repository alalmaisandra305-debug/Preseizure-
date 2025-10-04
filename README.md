# PreSeizure — Wearable AI Seizure Prediction

![PreSeizure Banner](https://via.placeholder.com/800x200.png?text=PreSeizure+Project)

**Author:** Sandra Ali Abdulhadi Alalmai  
**Age:** 16-year-old researcher  
**Project:** High-school research on predicting epileptic seizures using wearable sensors and AI  

---

## Overview
PreSeizure is a research project that explores whether **wearable sensors** (PPG heart-rate variability and accelerometers) combined with **AI models** can predict epileptic seizures **minutes before onset**.  

This project allowed me to learn how to:
- Collect and process physiological signals  
- Extract meaningful features like HRV and motion statistics  
- Build baseline and deep learning models (Random Forest, 1D-CNN, LSTM)  
- Interpret results using SHAP explainability  
- Visualize data through graphs and charts  

> "I had so much fun working on this project — designing models, testing signals, and building prototypes felt like real science. I love it!" — Sandra

---

## Methods
1. **Signal Processing:** Sliding windows on PPG and accelerometer data  
2. **Feature Extraction:** HRV time-domain features, motion statistics  
3. **Models:** Random Forest baseline, 1D-CNN, LSTM  
4. **Evaluation:** Event-level metrics (sensitivity, false alarm rate, median lead time)  
5. **Explainability:** SHAP for model interpretability  

---

## Sample Results
Simulated example metrics (demo purposes):
- Sensitivity: 87%  
- False alarms: 0.8/hr  
- Median lead time: 4.2 min  

Interactive graphs and animations are included in the website version of this project.

---

## Repository Contents
- `index.html` → Your website front page  
- Code notebooks and preprocessing scripts (optional links)  
- Dataset references (CHB-MIT EEG: [PhysioNet](https://physionet.org/content/chbmit/1.0.0/))  

---

## About the Researcher
**Sandra Ali Abdulhadi Alalmai** — 16-year-old high school researcher.  
I focused on bridging wearable sensing and AI to help people with epilepsy.  
I loved every part of this project, from hands-on experiments to understanding how models make predictions.  

**Contact:** [your-email@example.com]

---

## Live Website
Visit the project website here:  
[https://alalmaisandra305-debug.github.io/PreSeizure](https://alalmaisandra305-debug.github.io/PreSeizure)
