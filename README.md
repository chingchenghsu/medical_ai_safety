####  Enhancing Transparency and Safety in Medical AI through Model Calibration and Uncertainty decision Modeling

Project abstract: 
This project aims to investigate methods for improving the safety, transparency, and trustworthiness of machine learning models in healthcare applications. While deep learning has shown remarkable performance in tasks such as medical imaging and diagnosis, clinicians often hesitate to rely on these models due to their “black-box” nature and lack of calibrated confidence. The project will focus on two aspects: (1) Model Calibration — applying cutting-edge machine learning calibration methods to overcome the model over-confidential predictions and reduce model uncertainties  (test-time data augmentation, and calibration methods like Platt scaling). (2) Risk-aware decision process  — there is a gap from model outcomes to final doctor decisions. Risk-aware decision making is a framework where decisions are made not just based on predicted outcomes, but also by explicitly accounting for the uncertainty and potential consequences (risks) of those outcomes.  A possible consideration flow is like below: 

![image](decision_medical.png)


# 🚀 GPU Defect Detection System

An AI-powered system for detecting defects in GPU manufacturing using computer vision and Bayesian drift detection. The project integrates deep learning models with Statistical Process Control (SPC) methods to ensure high-quality production and proactive anomaly detection.

---

## 📌 Features
- 🔍 Automated defect detection from high-resolution GPU wafer images
- 📊 Intelligent SPC analysis with Bayesian drift detection
- ⚡ Fast inference with PyTorch and ONNX Runtime
- 📡 Real-time alert system integrated with email/Slack
- 🛠 Modular design for easy extension to other manufacturing processes

---

## 📂 Project Structure
```
gpu-defect-detection/
│── data/                # Sample training & test data
│── notebooks/           # Jupyter notebooks for exploration & experiments
│── src/                 
│   ├── models/          # Deep learning models
│   ├── pipelines/       # Preprocessing & defect detection pipeline
│   └── monitoring/      # Drift detection & SPC modules
│── tests/               # Unit and integration tests
│── requirements.txt     # Python dependencies
│── README.md            # Project description
│── LICENSE              # License file
```

---

## ⚙️ Installation
```bash
git clone https://github.com/your-username/gpu-defect-detection.git
cd gpu-defect-detection
pip install -r requirements.txt
```

---

## 🚦 Usage
1. Prepare your dataset in the `data/` folder  
2. Train the defect detection model:  
   ```bash
   python src/train.py --config configs/train.yaml
   ```  
3. Run inference on test images:  
   ```bash
   python src/infer.py --input data/test/
   ```  
4. Start drift detection monitoring:  
   ```bash
   python src/monitoring/drift_detect.py
   ```

---

## 📊 Example Results
- Defect classification accuracy: **96.3%**
- Bayesian drift detection reduced false alarms by **40%**
- Real-time alerts delivered within **3 seconds**

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

---

## 📜 License
This project is licensed under the MIT License.

