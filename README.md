# Prescription Monitoring System

This is a web-based prescription safety checker built with Streamlit. It helps healthcare providers validate prescriptions by checking for:

- Drug–drug interactions
- Allergies
- Contraindications
- Dose range violations
- Prescription guideline adherence

It also generates a downloadable PDF report of the results.

## Features

- Simple and intuitive dashboard
- Patient and prescription input form
- Automated alerts based on predefined rules
- PDF export of prescription safety report

## How to Use

1. Enter the patient's name, age, allergies, conditions, and diagnosis.
2. Input the prescribed drugs and doses.
3. Click **"Run Check"** to see any safety alerts.
4. Download the generated PDF report.

## Deployment

This app is hosted on [Streamlit Cloud](https://streamlit.io/cloud) and can also be run locally:

```bash
pip install -r requirements.txt
streamlit run app.py
