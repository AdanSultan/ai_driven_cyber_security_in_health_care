# AI-Driven Cyber Security in Healthcare  
## Using Adaptive Neural Networks for Threat Detection and Data Protection

---

## Project Overview

This project presents an **AI-driven cybersecurity framework for healthcare systems** using **adaptive deep learning models**.  
A hybrid **CNN–LSTM architecture** is proposed to perform **threat detection, intrusion analysis, and data protection validation** in healthcare environments.

The system is evaluated across **cybersecurity and healthcare datasets** to demonstrate robustness, adaptability, and high detection performance.

---

## Research Objective

Healthcare systems are highly vulnerable to cyber threats due to the sensitive nature of medical data and critical infrastructure requirements.  
Traditional security approaches often fail to adapt to evolving attack patterns.

This project aims to:
- Detect cyber threats using deep learning
- Validate AI robustness in real healthcare data environments
- Support secure and intelligent healthcare systems

---

## Model Architecture

The proposed model is an **Adaptive Hybrid CNN–LSTM Network**:

- **Convolutional Neural Network (CNN)**  
  Extracts spatial and statistical features from input data.

- **Bi-directional LSTM (Long Short-Term Memory)**  
  Captures temporal dependencies and sequential behavior.

- **Adaptive Design**  
  The same architecture is applied across multiple datasets to test generalization.

---

## Datasets Used

### 1. NSL-KDD / DrDoS Dataset (Primary Cybersecurity Evaluation)

- Domain: Network Security  
- Purpose: Intrusion and DDoS attack detection  
- Role: **Primary evidence for cybersecurity performance**

This dataset is used to evaluate the model’s ability to distinguish between **normal and malicious network traffic**.

---

### 2. MIMIC-III Clinical Database (Healthcare Environment Validation)

- Domain: Healthcare  
- Purpose: Real-world clinical data simulation  
- Role: **Healthcare data protection and adaptability validation**

> **Important Note:**  
> MIMIC-III is **not used as a cyberattack dataset**.  
> It is used to validate the robustness and adaptability of the AI model within healthcare data environments.

---

## Implementation Details

- Framework: PyTorch  
- Language: Python  
- Environment: Google Colab (GPU-supported)  
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix (percentage-based)

---

## Experimental Results

- **Cybersecurity Dataset Accuracy:** ~99.66%  
- High precision, recall, and F1-score  
- Clear separation between attack and normal traffic  
- Stable training and validation performance

Graphs, confusion matrices, and comparison charts are generated during execution.

---

## Repository Structure

ai_driven_cyber_security_in_health_care/
│
├── ai_driven_cyber_security_in_health_care.ipynb
├── README.md
└── sample_data / datasets (loaded via Colab)



---

## How to Run the Project

1. Open the notebook in Google Colab  
2. Upload required datasets when prompted  
3. Run cells sequentially  
4. Observe training, evaluation, and visual outputs

---

## Key Contributions

- AI-driven cybersecurity framework for healthcare
- Adaptive CNN–LSTM architecture
- Cross-domain validation using healthcare data
- High-performance intrusion detection results

---

## Applications

- Healthcare cybersecurity systems  
- Hospital network protection  
- Medical data security  
- AI-based intrusion detection systems (IDS)

---

## Disclaimer

- NSL-KDD / DrDoS is used for **cyber threat detection**
- MIMIC-III is used strictly for **healthcare environment validation**
- No medical diagnosis or patient-level inference is performed

---

## License

This project is intended for academic, research, and educational purposes.
