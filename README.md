# A QR Code Scam Detection Tool Using Machine Learning Algorithms for Real-Time Threat Analysis

This repository contains the **QR Code Scam Detector**, primarily developed using **Jupyter Notebook** and **Python**.

---

## 📁 Contents

The language composition of this repository is:
- **Jupyter Notebook**: 82.9%
- **Python**: 17.1%

---

## ✅ Prerequisites

To run the code in this repository, you will need:

- Python 3.x
- Jupyter Notebook

## 🚀 Usage

### ▶️ Running Jupyter Notebooks

To start using the Jupyter Notebooks in this repository, run:

```sh
jupyter notebook
```

Then, open the notebooks you want to explore and run the cells.

---

### ▶️ Running the Python Script

To run the Python script for QR code checking, use the following command:

```sh
python qr_checker.py --image testimage3.png --csv results.csv --json results.json
```

Replace `testimage3.png`, `results.csv`, and `results.json` with your desired input image and output file names.

---

## 🤝 Contributing

If you would like to contribute to this project, please follow these steps:

1. **Fork the repository**  
2. **Create a new branch**:
   ```sh
   git checkout -b feature-branch
   ```
3. **Make your changes**  
4. **Commit your changes**:
   ```sh
   git commit -m "Add some feature"
   ```
5. **Push to the branch**:
   ```sh
   git push origin feature-branch
   ```
6. **Open a pull request**

## 📌 Project Overview

This project presents a smart and secure *QR Code Scam Detection Tool* that utilizes *machine learning algorithms* to identify and flag potentially malicious or fraudulent QR codes in real time. The system analyzes encoded URL patterns and associated metadata to detect scams, ensuring user safety during QR interactions.

---

## 🚀 Key Features

•⁠  ⁠📷 Scan and extract data from QR codes
•⁠  ⁠🧠 Use machine learning models (e.g., Logistic Regression, Random Forest) to detect scam patterns
•⁠  ⁠🔐 Flag suspicious URLs and redirection behaviors
•⁠  ⁠📊 Real-time analysis with immediate threat feedback
•⁠  ⁠🌐 Optional UI using *Streamlit* or *Flask*

---

## 🧠 Technologies Used

•⁠  ⁠*Python 3.10+*
•⁠  ⁠*OpenCV* – QR Code detection from images
•⁠  ⁠*Pandas, **NumPy* – Data preprocessing
•⁠  ⁠*Scikit-learn* – ML algorithms (classification)
•⁠  ⁠*Joblib* – Model serialization
•⁠  ⁠*Streamlit / Flask* – UI for real-time detection
•⁠  ⁠*Jupyter Notebook* – Analysis and model training

---
## sample outputs

![image](https://github.com/GudepuRakshitha/A-QR-Code-Scam-Detection-Tool-Using-Machine-Learning-Algorithms-for-Real-Time-Threat-Analysis-/blob/19deba2d6b87f67c15b19702fe0cad9ba9225fd4/qr1.png)

![image](https://github.com/GudepuRakshitha/A-QR-Code-Scam-Detection-Tool-Using-Machine-Learning-Algorithms-for-Real-Time-Threat-Analysis-/blob/19deba2d6b87f67c15b19702fe0cad9ba9225fd4/qr2.png)

![image](https://github.com/GudepuRakshitha/A-QR-Code-Scam-Detection-Tool-Using-Machine-Learning-Algorithms-for-Real-Time-Threat-Analysis-/blob/19deba2d6b87f67c15b19702fe0cad9ba9225fd4/qr3.png)

![image](https://github.com/GudepuRakshitha/A-QR-Code-Scam-Detection-Tool-Using-Machine-Learning-Algorithms-for-Real-Time-Threat-Analysis-/blob/19deba2d6b87f67c15b19702fe0cad9ba9225fd4/qr4.png)

---

## ⚙️ How It Works

1.⁠ ⁠*Scan QR Code*: Extracts encoded text (usually a URL) using OpenCV or pyzbar.
2.⁠ ⁠*Preprocess Input*: Extracts URL features like domain, path length, presence of special characters, etc.
3.⁠ ⁠*Classification*: Uses a trained ML model to classify the URL as Safe or Scam.
4.⁠ ⁠*Display Result*: Shows threat level with justification (e.g., contains phishing keywords, uses URL shortener, etc.)

---

### ✅ Setup Environment

pip install -r requirements.txt
Run Detection Script: python detector.py --image ./data/sample_qr.png
Launch Streamlit App: streamlit run app.py

## Sample Output 
QR Scan Result:
URL: http://bit.ly/secure-login-page
⚠️ Alert: This QR code redirects to a suspicious domain.
Threat Type: URL Shortener + Phishing Keywords
Prediction: SCAM

## Future Enhancements
🔁 Live camera QR scanning integration

🧠 Deep Learning-based scam detection (e.g., LSTM, BERT for URL)

🌍 Integration with online URL threat intelligence APIs

📱 Android/iOS App using React Native or Flutter


## 🙏 Acknowledgments

Thank you for using **QR code Scam Detector**.  
If you have any questions or feedback, feel free to open an issue or contact the maintainer.

---

## 🧠 Code

Feel free to modify this project to better suit your needs!

## ✍️ Author

**Natuva Bhavana**  

Email: natuvabhavana@gmail.com
