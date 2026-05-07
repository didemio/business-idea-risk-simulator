# 🧠 BIRS — Business Idea Risk Simulator

A web-based decision support tool that helps entrepreneurs and students evaluate the risk level of their early-stage business ideas.

---

## 📌 About the Project

BIRS allows users to submit a business idea along with key parameters and receive a structured risk analysis. The system calculates risk scores across three categories — **Market Risk**, **Resource Risk**, and **Adoption Risk** — and aggregates them into an overall **Risk Index** (0–100), classifying the idea as **Low**, **Medium**, or **High** risk.

This project was developed as a university study project based on a Software Requirements Specification and System Design Description.

---

## ✨ Features

- 📝 **Idea Submission Form** — Enter your business idea name, description, and industry
- 🎨 **Auto Logo Generator** — Generates a color-coded logo based on your business name and industry
- 🔍 **Similar Business Lookup** — Finds real-world similar businesses based on your description, filtered by region (Europe / America / Asia)
- ⚖️ **Risk Calculation Engine** — Weighted scoring across 6 parameters using sliders
- 📊 **Risk Analysis Dashboard** — Visual display of Risk Index and category scores with progress bars
- 📋 **Detailed Risk Report** — Category-by-category analysis with strategic recommendations

---

## 🧮 How Risk is Calculated

Risk is evaluated across three categories using a **weighted scoring method**:

| Category | Parameters |
|---|---|
| Market Risk | Market size + Competition level |
| Resource Risk | Estimated budget + Team experience |
| Adoption Risk | Technical complexity + Target audience size |

Each slider maps to a value between 1–5, which is converted to a 0–100 score. The three category scores are averaged into a final **Risk Index**.

| Risk Index | Classification |
|---|---|
| 0 – 30 | 🟢 Low Risk |
| 31 – 70 | 🟡 Medium Risk |
| 71 – 100 | 🔴 High Risk |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Page structure |
| CSS | Styling and layout |
| JavaScript | Risk logic, interactivity, keyword matching |

No frameworks, no external libraries, no backend required. Runs entirely in the browser.

---

## 🚀 Getting Started

### Option 1 — Open directly
Double-click `index.html` to open in your browser.
> ⚠️ Some features may be limited when opening via `file://` protocol.

### Option 2 — Run with local server (recommended)
```bash
# Navigate to the project folder
cd BIRS

# Start a local server
python -m http.server 8000
```
Then open your browser and go to:
```
http://localhost:8000
```

---



## 📄 Related Documents

- Test Report (BIRS_Test_Report.pdf)

---

## 👩‍💻 Author

Developed as a university study project — Riga, 2026.
