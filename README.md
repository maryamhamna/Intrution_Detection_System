🛡️ GuardX — AI-Powered Intrusion Detection System (IDS) Prototype
🌟 Project Overview

GuardX is an AI-driven Intrusion Detection System (IDS) prototype developed during a hackathon to strengthen cybersecurity defenses.
The system analyzes URLs in real time to identify and prevent potential threats before they can impact users.

🔑 Key Features

✅ Detects whether a URL is safe or malicious

✅ Assigns threat risk levels: Low, Medium, High, Critical

✅ Categorizes threat types:

Malware

Phishing

Defacement

Benign

✅ Extracts essential information such as:

IP address

Hosting country

✅ Displays detection confidence scores

✅ Verifies whether a URL is blacklisted

✅ Provides bar graph visualizations for clearer threat analysis

🔍 Dataset Utilized

The AI model was trained and tested using a malicious URL detection dataset that includes:

Phishing URLs

Defacement URLs

Benign URLs

Supporting metadata such as IP addresses, hosting locations, and blacklist indicators

This dataset enables GuardX to accurately classify URLs and assess their associated risks.

| Component          | Description                                          |
| ------------------ | ---------------------------------------------------- |
| Python             | Core backend logic and AI model implementation       |
| Streamlit          | Interactive and user-friendly web interface          |
| Machine Learning   | Threat detection and classification model            |
| Data Visualization | Bar charts for risk assessment and confidence levels |

🚀 Planned Enhancements

To improve threat isolation and system security, future versions of GuardX will integrate Docker-based virtualization:

Suspicious or malicious URLs will open in a secure sandboxed environment

Virtual environments will terminate automatically after execution

Prevents direct exposure to the host system

These improvements will transform GuardX into a more robust, proactive cybersecurity solution.

📜 License

This project is intended for educational and demonstration purposes only and was developed as a hackathon prototype.

© 2025 Team GuardX
