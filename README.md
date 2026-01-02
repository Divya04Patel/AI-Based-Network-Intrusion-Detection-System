# AI-Based Network Intrusion Detection System (NIDS)

An **AI-powered Network Intrusion Detection System** that uses Machine Learning to detect anomalous traffic in real time, with an interactive Streamlit dashboard for visualization and experimentation. [file:1]

---

## Features

- Real-time packet-level intrusion detection using a Random Forest classifier. [file:1]  
- Interactive Streamlit dashboard for model training, monitoring, and traffic simulation. [file:1]  
- Built-in synthetic traffic generator for instant demos without external datasets. [file:1]  
- Optional integration with the CIC-IDS2017 benchmark dataset for realistic experiments. [file:1]  
- Visual analytics for traffic distribution, feature importance, and prediction outcomes. [file:1]

---

## Tech Stack

- **Language:** Python 3.8+ [file:1]  
- **ML Library:** scikit-learn (Random Forest) [file:1]  
- **Data & Numerics:** pandas, numpy [file:1]  
- **Visualization & UI:** Streamlit, seaborn, matplotlib [file:1]  
- **Environment:** VS Code / any Python IDE, terminal (CMD / PowerShell / Linux/macOS shell) [file:1]

---

## Project Structure

```bash
AI-NIDS-Project/
├─ nids_main.py        # Main Streamlit app and ML pipeline
├─ requirements.txt    # Project dependencies
├─ data/
│  └─ CIC-IDS2017.csv  # (Optional) Real traffic dataset file
└─ README.md
