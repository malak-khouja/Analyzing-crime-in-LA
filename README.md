# Analyzing-crime-in-LA

Los Angeles, California — The City of Angels 🌴  
Behind its glamour and cultural influence, Los Angeles faces significant crime challenges.  
This project analyzes crime data from the Los Angeles Police Department (LAPD) to uncover
patterns in criminal behavior and support better resource allocation.

---

## 📊 Project Objectives

- Analyze crime distribution across geographic areas
- Identify peak crime hours
- Detect areas with high night crime activity
- Study victim demographics (age and sex)
- Provide actionable insights through data visualization

---

## 🗂 Dataset Description

The dataset is a modified version of the official LAPD crime data and includes:

| Column | Description |
|------|------------|
| DR_NO | Official crime report number |
| Date Rptd | Date the crime was reported |
| DATE OCC | Date the crime occurred |
| TIME OCC | Time of occurrence (24-hour format) |
| AREA NAME | LAPD patrol division |
| Crm Cd Desc | Crime description |
| Vict Age | Victim age |
| Vict Sex | Victim sex |
| Vict Descent | Victim descent |
| Weapon Desc | Weapon used (if any) |
| Status Desc | Crime status |
| LOCATION | Crime location |

---

## 🧪 Methodology

- Data cleaning and type conversion
- Handling missing and inconsistent values
- Outlier detection using the IQR method
- Temporal analysis (hourly and night crimes)
- Spatial analysis by patrol area
- Demographic analysis using age groups

---

## 📈 Key Insights

- **Peak crime hour:** 12:00 PM
- **Highest night crime area:** Central
- Crimes are unevenly distributed across areas
- Adults aged **26–44** represent a significant proportion of victims

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Future Improvements

- Crime trend analysis over time
- Predictive modeling for crime occurrence
- Interactive dashboard (Power BI / Streamlit)
- Integration with geospatial maps

---

## 👩‍💻 Author

**Malak Khouja**  
Data Science & AI Enthusiast  
Full-Stack Developer in Training

---

📎 *This project is for educational and analytical purposes.*
