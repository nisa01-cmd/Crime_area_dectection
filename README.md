# 🕵️‍♀️ Crime Area Detection System using Data Warehouse and Data Mining

## 📌 Project Overview

The **Crime Area Detection System** is an intelligent solution designed to identify and predict crime-prone areas (hotspots) using structured crime data and advanced data mining techniques. By integrating data warehousing and mining, this system aims to support law enforcement agencies, researchers, and city planners in making data-driven decisions for crime prevention.

---

## 🎯 Problem Statement

With the rise in urban crime and the growing volume of crime data generated daily, it becomes challenging for authorities to manually analyze, identify patterns, and make timely interventions. Existing systems often lack centralized, structured storage and fail to harness predictive analytics effectively.

There is a pressing need for a system that can consolidate data from various sources, extract meaningful insights, and visualize crime-prone areas on a map in a user-friendly way.

---

## 💡 Ideal Solution

This project proposes a system that:
- Builds a centralized **Data Warehouse** for storing structured crime data.
- Utilizes **ETL pipelines** to extract, clean, and transform raw data.
- Applies **data mining algorithms** (clustering, classification, association) to discover crime patterns.
- Provides a **web dashboard** with heatmaps, filters, and downloadable reports for real-time analysis.

---

## 🧱 System Architecture

```

\[Data Sources]
↓
\[ETL Process: Extract → Transform → Load]
↓
\[Crime Data Warehouse (Star Schema)]
↓
\[Data Mining Engine: Clustering | Classification | Association]
↓
\[Web-based User Interface with Map and Analytics]

```

---

## 🧑‍💼 Target Users

- Police departments and law enforcement agencies
- Urban safety planners
- Researchers and data analysts
- Public safety organizations

---

## 🛠️ Tech Stack

| Layer            | Technology Used                              |
|------------------|-----------------------------------------------|
| Data Sources     | Public datasets (CSV, APIs, FIRs, CCTV data) |
| ETL              | Python (Pandas, SQLAlchemy), Airflow (optional) |
| Data Warehouse   | MySQL / PostgreSQL                           |
| Data Mining      | Python (scikit-learn, mlxtend, NumPy, Matplotlib) |
| Backend API      | Flask / Django                               |
| Frontend UI      | HTML, CSS, JavaScript, Google Maps API       |
| Dashboard        | Chart.js / Leaflet / D3.js                   |

---

## 📊 Key Features

- 🔍 Crime heatmap with filterable locations and timelines
- 📌 Real-time crime clustering (hotspot detection)
- 🧠 Predictive model for upcoming crime zones
- 📈 Graphs and statistics by crime type, area, and time
- 📝 Report generation and export (PDF/CSV)
- 🔔 Alert system based on threshold crime frequency

---

## 🗂️ Folder Structure

```

crime-detection-system/
│
├── data/                # Raw & processed datasets
├── etl/                 # ETL scripts (Python)
├── warehouse/           # SQL schema and dump
├── mining/              # Clustering, classification, forecasting scripts
├── frontend/            # HTML, CSS, JS, templates
├── backend/             # Flask or Django app files
├── reports/             # Generated reports
└── README.md

````

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/crime-detection-system.git
cd crime-detection-system
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Setup the Database

* Create a MySQL/PostgreSQL database
* Import the schema from `warehouse/schema.sql`
* Run the ETL script to populate data

### 4. Start the Backend Server

```bash
python app.py  # For Flask
# or
python manage.py runserver  # For Django
```

### 5. Launch the Frontend

Open `frontend/index.html` in your browser.

---

## 📂 Sample Datasets

You can use:

* [Indian Crime Data](https://data.gov.in/)
* [Kaggle - Crime in Chicago](https://www.kaggle.com/datasets/chicago/crime)
* [OpenCrime Data APIs](https://data.police.uk/)

---

## 🧠 Algorithms Used

* **Clustering**: K-Means for hotspot detection
* **Classification**: Random Forest / Decision Trees for crime type prediction
* **Association Rules**: Apriori / FP-Growth for crime pattern analysis
* **Time Series Forecasting**: ARIMA or Facebook Prophet (optional)

---

## 📌 Future Improvements

* Real-time data ingestion via APIs
* Integrate CCTV video analytics
* Mobile app version for field use
* AI-based crime severity scoring

---

## 🙌 Contributors

* \[NTG] – Project Lead & Developer
* \[Dhwani. Chaitrali, Preeti]
