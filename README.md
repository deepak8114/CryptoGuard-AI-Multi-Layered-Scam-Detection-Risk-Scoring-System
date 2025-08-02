# CryptoGuard-AI-Multi-Layered-Scam-Detection-Risk-Scoring-System
An AI-powered, multi-layered scam detection and risk scoring system for cryptocurrency platforms. Combines anomaly detection, NLP-based scam URL classification, SHAP explainability, and real-time alerts to protect users, support compliance, and build trust across Web3.

##  Project Overview

Every year, billions of dollars are lost to crypto-related scams — from fake airdrops and phishing links to complex rug pulls. Existing tools are reactive, fragmented, and often lack transparency.

**CryptoGuard AI** solves this with a proactive, explainable, and scalable detection system that:

- Flags risky wallets based on blockchain transaction behavior  
- Identifies scam websites using NLP techniques  
- Combines insights via an ensemble risk scoring engine  
- Generates real-time alerts with full model explainability using SHAP

---

##  Core Features

-  **Anomaly Detection:** Isolation Forest + One-Class SVM to detect abnormal wallet behavior
-  **NLP-based Scam URL Classification:** Logistic Regression + TF-IDF to detect scammy links
-  **Explainable AI (SHAP):** Feature importance visualizations to ensure trust & transparency
-  **Ensemble Risk Scoring Engine:** Merges multiple model outputs for smarter predictions
-  **User & Platform Alerts:** Real-time warnings for exchanges, wallets, and end-users
-  **Scam Glossary & Awareness Module:** Educates users with real-world scam patterns

---

##  Architecture
┌─────────────┐
    │ Transaction │
    │   Dataset   │
    └────┬────────┘
         │
         ▼
┌────────────────────┐
│ Anomaly Detection │ ◄────────┐
└────────────────────┘ │
│ ├──► Ensemble Risk Score
▼ │
┌────────────────────┐ │
│ NLP Scam URL Class │ │
└────────────────────┘ │
│ │
▼ │
┌──────────────────────┐ │
│ SHAP Explainability │ ◄──┘
└──────────────────────┘
##  Model Performance

- **Transactions analyzed**: 9,800+  
- **URLs classified**: 2,000+  
- **High-risk patterns detected**: 766+  
- **Metrics used**: F1 Score, Precision, Recall, ROC-AUC  
- **Visuals**: SHAP plots, heatmaps, scam word clouds, risk alert UI mockups

---

##  Dataset Sources

-  Transaction Behavior Dataset (synthetic + real samples)
-  Labeled URLs/URIs: Scam vs Non-Scam
-  Structured Scam Glossary (25+ scam types)
-  Synthesized high-risk behavior for training/testing
## Business Use Cases

- **Crypto Exchanges**: Flag suspicious activity in real time
- **Wallet Providers**: Warn users before risky transfers
- **Governments & Regulators**: Support AML/CTF enforcement
- **Civilians & Investors**: Safer and more informed crypto experience

---

##  Future Roadmap (Next 15 Years)

-  Integrate Graph Neural Networks (GNNs) for scam ring detection  
-  NLP monitoring of Twitter, Telegram, and Discord scam chatter  
-  Global Scam Registry for public + regulatory use  
-  Launch a full **Crypto Awareness Platform**  
-  Real-time dashboard + browser extension for mass protection

---

##  Tech Stack

- `Python`, `scikit-learn`, `SHAP`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- `TF-IDF`, `Logistic Regression`, `Isolation Forest`, `One-Class SVM`
- `Flask` / `FastAPI` (for deployment)
- `Streamlit` (for frontend demo/dashboard)
- `GitHub`, `Jupyter`, `PowerPoint`

---

##  References

See [`Resources.txt`](./presentation/Resources.txt) for all datasets, research papers, and technical guides used.

---

##  Author

**Deepak Patro**  
📧 [deepakpatro73@@gmail.com](mailto:deepakpatro73@gmail.com)  
🔗 [LinkedIn](linkedin.com/in/deepak-patro-2a0330228)  
💻 GitHub: [Deepak8114](https://github.com/deepak8114)

