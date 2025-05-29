# ⚡ Grid Data Cleaning Tool

A lightweight Python-based toolset for cleaning, validating, and preparing grid-related datasets — including SCADA logs, smart meter readings, and other energy infrastructure files — for downstream analysis.

---

## 🔍 Overview

Grid data is often messy, inconsistent, and difficult to use directly in analytics or reporting pipelines. This tool provides a modular approach to pre-process energy data for use in forecasting, performance analysis, or dashboarding.

It includes utilities for:
- Timestamp normalization and time zone alignment
- Missing value detection and handling
- Duplicate entry removal
- Data type coercion and sanity checks
- Logging and reporting of cleaned elements

---

## ⚙️ Use Cases

This tool is designed for:
- **Energy analysts** working with smart meter data or SCADA systems.
- **Data scientists** preparing energy datasets for modelling.
- **Freelancers and consultants** supporting digitalization in energy utilities.

It has been tested with:
- Hourly and sub-hourly SCADA logs (CSV format)
- Smart meter exports (Excel and CSV)
- Aggregated load profiles from LV/MV substations

---

## 📂 Project Structure

```
grid-data-cleaning-tools/
│
├── data/                  # Sample raw and cleaned datasets
├── scripts/
│   ├── clean_scada.py     # Core cleaning pipeline
│   └── utils.py           # Helper functions (logging, validation)
├── notebooks/
│   └── cleaning_demo.ipynb  # Walkthrough of tool in action
├── docs/
│   └── schema_example.md   # Example input formats and field definitions
├── requirements.txt
└── README.md
```

---

## 🚀 Quick Start

1. **Clone the repo**
```bash
git clone https://github.com/your-username/grid-data-cleaning-tools.git
cd grid-data-cleaning-tools
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the cleaning script**
```bash
python scripts/clean_scada.py --input data/raw_log.csv --output data/cleaned_log.csv
```


---

## 📈 Example Output

- Cleaned and aligned timestamps (UTC)
- Report of removed/null/duplicate values
- Ready-to-use dataset for visualization or modelling

---

## 🧠 About the Author

I'm a renewable energy expert and electrical engineer with hands-on experience in grid automation, data-driven analysis, and digitalization of the energy sector. I now help companies and professionals turn raw data into clean, actionable insights.

---

## 📫 Contact

If you'd like to collaborate or use this tool in a project, feel free to reach out:

- Email: edbarajash@gmail.com  
- LinkedIn: https://www.linkedin.com/in/eduar-barajas/

---
