# 🧪 Prostate Cancer Data Exploration (Simulacrum Challenge)

Welcome to our collaborative project for the **2025 HDRUK Health Data Science Technical Challenge**.  We'll be exploring synthetic prostate cancer patient data (simulacrum_v2.1.0) using Python.
This repository contains all code, notebooks, and documentation related to the project.

---

## 📌 Project Overview

We are working with a synthetic dataset from the [Simulacrum Project](https://simulacrum.healthdatainsight.org.uk/) that mimics English cancer patient data. Our task is to explore the **prostate cancer (ICD-10: C61)** subset and summarize key findings for a healthcare-informed audience.

### Objectives:
- Understand the structure and variables within the dataset
- Perform exploratory data analysis (EDA)
- Identify trends, patterns, and correlations
- Communicate findings visually and clearly
- Highlight the dataset’s reliability and limitations

---

## 🔧 Tools & Technologies

- [Google Colab](https://colab.research.google.com) – Cloud-based Python coding
- [GitHub](https://github.com/ogeohia/HDRUK-group9-prostate-cancer-exploration) – Code version control and collaboration
- [Slack](https://group9hdruk.slack.com/) – Team communication
- [Teams](https://teams.microsoft.com/l/meetup-join/19:meeting_MWM1MzBkOTgtZTNkYi00NmFkLWJkYjUtZDg4NzFiZTRhNzc3@thread.v2/0?context=%7B%22Tid%22:%222b897507-ee8c-4575-830b-4f8267c3d307%22,%22Oid%22:%2269cac2af-f7ae-48fe-b493-0720125830a2%22%7D) – Weekly meetings and discussion

---

## 🗂 Repository Structure

```
group9-prostate-cancer-exploration/
├── notebooks/           # Google Colab notebooks
├── data/                # Input data files (not pushed to GitHub) ⚠️ DO NOT UPLOAD large data files here
│   └── README.md           # Explains where to access data externally
├── outputs/             # Visualizations, tables, or analysis results
├── docs/                # Reports, slides, or literature references
├── requirements.txt     # Python dependencies
├── CONTRIBUTORS.md      # Team members and roles
├── README.md            # Project overview 
└── .gitignore           
```
---

## 📁 Data Access

To manage storage and maintain performance, we are **not storing the dataset in this repository**.

📦 Dataset Location:  
We are using a shared Google Drive folder to store the large datasets:  
👉 [Access the Google Drive Folder (View Only)](https://drive.google.com/drive/folders/1W8UfSTsaS1U2G4RiHyCT6BHID6FLxvpH?usp=sharing)

Please do **not upload** large `.csv` or `.xlsx` files to the GitHub `data/` folder.

---

## 🧠 Team Notebook Management Policy

To avoid overwriting issues and maintain a clean collaboration workflow, all team members should follow this notebook policy:

### ✅ 1. Use Personal Notebook Copies

Each member should create their own notebook copy when making edits.

**File naming format:**
```
notebooks/<serial-number>_<task>_<yourname>.ipynb
```

**Examples:**
- `notebooks/01_intial-exploration_Oge.ipynb`
- `notebooks/02_univariate-analysis_Hayat.ipynb`
- `notebooks/03_handle-missing-values_Muhinya.ipynb`

---

### 🔒 2. Do Not Edit Someone Else’s Notebook

Please don’t modify another member’s `.ipynb` unless asked to. If you need to extend their work:
- Copy their notebook
- Rename it using the naming format above

---

### 💬 3. Add Clear Commit Messages

When saving to GitHub, please describe your changes:
```
"Added treatment trend graph by year"
"Fixed NaN bug in age column"
```

---

## 👥 Team Members

See `contributors.md` for list of members and assigned focus areas.

---

## 📦 Setup Instructions

Install the required Python packages:
```bash
pip install -r requirements.txt
```

---

Feel free to contribute via pull requests or by uploading your notebooks following the structure above.

Happy coding! 🚀
