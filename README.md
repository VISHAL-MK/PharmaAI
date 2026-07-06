# 💊 PharmaAI-MediTrust
### AI-Powered Medicine Verification & Drug Safety Platform

PharmaAI-MediTrust is an AI-based medicine verification system that helps users verify medicine authenticity, detect counterfeit drugs, identify drug interactions, and generate safety reports using OCR, public healthcare APIs, and machine learning.

The platform extracts medicine details from images or text, validates them against trusted medical databases, analyzes possible drug interactions, and provides an easy-to-understand risk assessment.

---

# 🚀 Features

- 📷 OCR-based medicine label extraction
- ✅ Medicine authenticity verification
- 💊 Drug interaction detection
- 🔍 Batch number verification
- 📄 Automatic risk report generation
- 🌐 REST API using FastAPI
- 🖥️ Interactive frontend dashboard
- 🌍 Multilingual support using Sarvam AI
- 📦 JSON report export
- 📊 Medicine safety analysis

---

# 🛠️ Technologies Used

## Backend
- Python
- FastAPI
- Uvicorn

## Frontend
- HTML
- CSS
- JavaScript

## Database
- MongoDB

## AI & APIs
- Sarvam AI
- RxNorm API
- OpenFDA API
- PubChem API

## Libraries
- Requests
- Pillow
- OpenCV
- NumPy
- Pyzbar
- Bcrypt
- Python-JOSE
- HTTPX

---

# 📁 Project Structure

```
PharmaAI-MediTrust/
│
├── core/
│   ├── batch_verify.py
│   ├── interactions.py
│   ├── meditrust_db.py
│   ├── ocr_fixed.py
│   ├── report.py
│   └── resolver.py
│
├── frontend/
│   ├── index.html
│   └── dashboard.html
│
├── data/
│   └── Demo verification dataset
│
├── reports/
│   └── Generated JSON reports
│
├── uploads/
│   └── Uploaded medicine images
│
├── tests/
│
├── api_bridge.py
├── main.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## Clone the repository

```bash
git clone https://github.com/yourusername/PharmaAI-MediTrust.git
cd PharmaAI-MediTrust
```

## Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## Start the FastAPI Backend

```bash
uvicorn api_bridge:app --reload
```

or

```bash
python main.py
```

---

## Open Frontend

Simply open

```
frontend/index.html
```

or

```
frontend/dashboard.html
```

in your browser.

---

# 🧪 Usage

### Image Verification

Upload a medicine image.

The system will:

- Extract text using OCR
- Identify the medicine
- Verify authenticity
- Detect suspicious medicines
- Generate a safety report

---

### Text Verification

Enter the medicine name manually.

Example:

```
Paracetamol
```

or

```
Metformin
```

The application fetches:

- Generic name
- Drug information
- Manufacturer details
- Drug interactions
- Safety recommendations

---

# 🔄 Workflow

```
Medicine Image
        │
        ▼
OCR Extraction
        │
        ▼
Medicine Identification
        │
        ▼
Medicine Verification
        │
        ▼
Drug Interaction Analysis
        │
        ▼
Risk Assessment
        │
        ▼
Safety Report Generation
```

---

# 📊 APIs Used

| API | Purpose |
|------|----------|
| RxNorm | Drug Identification |
| OpenFDA | Medicine Labels & Safety Data |
| PubChem | Chemical Information |
| Sarvam AI | OCR, Translation & AI Processing |

---

# 📄 Generated Reports

The system automatically generates reports containing:

- Medicine Information
- Generic Name
- Manufacturer
- Drug Authenticity Status
- Counterfeit Indicators
- Drug Interactions
- Risk Level
- Medical Recommendations

Reports are saved inside:

```
reports/
```

---

# 📦 Requirements

Major dependencies include:

- FastAPI
- Requests
- Pillow
- OpenCV
- NumPy
- MongoDB
- Uvicorn
- Pyzbar
- Sarvam AI
- HTTPX

Install everything using:

```bash
pip install -r requirements.txt
```

---

# 🎯 Future Enhancements

- QR Code Authentication
- Blockchain-based Drug Tracking
- AI Counterfeit Detection
- Mobile Application
- Doctor Portal
- Pharmacy Dashboard
- CDSCO Integration
- DrugBank Integration
- Voice-based Medicine Search

---

# 👨‍💻 Contributors

Developed as an AI-powered healthcare solution for medicine verification and patient safety.

---

# 📜 License

This project is intended for educational and research purposes.

---

# ⭐ Acknowledgements

- OpenFDA
- RxNorm
- PubChem
- Sarvam AI
- FastAPI Community
- Python Open Source Community

---

## 📸 Sample Output

- Medicine authenticity status
- Drug interaction alerts
- Risk score
- JSON safety report
- Medicine information dashboard

---

## 💡 Project Objective

To provide an intelligent medicine verification platform that helps users identify counterfeit medicines, understand drug interactions, and improve medication safety through AI-powered analysis and trusted medical databases.
