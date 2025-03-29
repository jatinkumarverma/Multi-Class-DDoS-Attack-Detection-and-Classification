# Multi-Class DDoS Attack Detection and Classification

### 💻 Project Overview  
This project focuses on **multi-class classification** of Distributed Denial of Service (DDoS) attacks using machine learning and deep learning techniques. Unlike traditional approaches that only detect whether an attack is happening (binary classification), this work aims to identify **specific types of DDoS attacks** using the **CICDDoS2019** dataset. This helps in implementing more targeted and effective cybersecurity defenses.

---

### 📂 Dataset  
- **Name:** CICDDoS2019  
- **Source:** Canadian Institute for Cybersecurity  
- Contains both **reflection-based** and **exploitation-based** modern DDoS attack types such as:  
  - UDP Flood  
  - TCP SYN  
  - DNS Flood  
  - MSSQL Flood  
  - NetBIOS  
  - LDAP Flood  
  - SNMP  
  - SSDP  
  - WebDDoS  
  - TFTP  
- Dataset Size: ~26 GB

---

### ⚙️ Technologies Used  
- **Python 3.7**  
- **Libraries:**  
  - Scikit-learn  
  - TensorFlow  
  - Keras  
  - XGBoost  
  - Pandas  
  - NumPy  
  - Matplotlib  

---

### 🧑‍💻 Implemented Models  
1. **Machine Learning Models**  
   - Support Vector Machine (SVM)  
   - Decision Tree  
   - Random Forest  
   - AdaBoost  
   - XGBoost  

2. **Ensemble Learning Model**  
   - MV-4 Classifier (Majority Voting of RF, AdaBoost, DT, XGBoost)  

3. **Deep Learning Models**  
   - Multi-Layer Perceptron (MLP)  
   - Long Short-Term Memory (LSTM)  

---

### 🏆 Features  
✅ Multi-Class classification of DDoS attack types  
✅ Feature Selection using Extra Trees Classifier  
✅ Handles high-dimensional and real-world traffic data  
✅ Comparison of ML and DL models  
✅ Performance metrics: Accuracy, F1-score, ROC Curve  

---

### 📊 Results  
- Ensemble and Deep Learning models showed improved accuracy in detecting and classifying specific types of DDoS attacks.
- Multi-class classification helps in **fine-grained attack identification** leading to better cybersecurity defense strategies.

---

### 📄 Future Work  
- Further optimize deep learning models  
- Integrate real-time DDoS detection  
- Experiment with additional ensemble techniques  
- Deploy as an API for network security systems  

---
