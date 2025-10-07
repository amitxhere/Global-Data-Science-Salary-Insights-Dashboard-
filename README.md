# 💼 Global Tech Salary Insights Dashboard (Tableau Project)

This project provides a comprehensive analysis of global tech salaries based on job titles, experience levels, employment types, and countries. The dashboard was built in **Tableau Public** and is designed to help users explore salary patterns across different regions and professional roles.

<img width="1672" height="937" alt="image" src="https://github.com/user-attachments/assets/b5426c27-3874-4c18-a464-4fb807958e0d" />


---

## 📊 Dashboard Overview

### Key Visual Components:

#### 1. **Average Salary in USD by Experience and Employment Type**
- Visualizes average salaries segmented by:
  - Experience Level: Entry, Intermediate, Senior, Expert
  - Employment Type: Full-Time, Freelance, Part-Time, Contract

#### 2. **Total Companies by Size and Location**
- Donut chart showing company size distribution:
  - Small (13.67%)
  - Medium (53.71%)
  - Large (32.62%)

#### 3. **Map: Average Salary by Country**
- Choropleth map showing geographic variation in salary.
- Highlights salary ranges across countries.

#### 4. **Experience Level Distribution**
- Shows the percentage of employees in each experience category.
  - Senior: 46.13%
  - Intermediate: 35.09%
  - Entry: 14.50%

#### 5. **Employment Type Distribution**
- Majority are Full-Time (96.87%), with smaller percentages for Part-Time, Freelance, and Contract roles.

#### 6. **Top 10 Employee Residences**
- Horizontal bar chart showing top countries by number of respondents:
  - US (332), GB, IN, CA, DE, etc.

#### 7. **Average Salary by Job Title and Experience Level**
- Table view showing average salaries for various roles (e.g., AI Scientist, Data Analyst, ML Engineer) by experience level.

---

## 📁 Dataset Description

- **Source**: Likely sourced from Kaggle or open tech salary surveys (e.g., AI/ML job salary dataset)
- **Data Columns Include**:
  - Job Title
  - Experience Level
  - Company Size
  - Company Location
  - Employee Residence
  - Employment Type
  - Salary in USD
  - Work Year

---

## 🚀 How to Use This Dashboard

1. Open the Tableau file (`.twbx`) in [Tableau Public](https://public.tableau.com/s/download).
2. Use filters at the top to select:
   - Company Location
   - Job Title
3. Interact with visual components to analyze salary distributions across combinations of experience, employment type, and location.

---

## 🧰 Tools Used

- **Tableau Public**
- **Excel / CSV** (for initial dataset cleanup)
- **Mapbox** for the geospatial salary map

---

## 📂 Repository Contents

| File / Folder                 | Description                                       |
|------------------------------|---------------------------------------------------|
| `Global_Tech_Salary_Dashboard.twbx` | Tableau Packaged Workbook                         |
| `README.md`                  | Project overview and usage instructions          |
| `8596254b-e2fb-47d1-9fd1-f38bc9d75348.png` | Dashboard screenshot image                      |
| `dataset.csv` *(optional)*   | Cleaned dataset used in Tableau (if applicable)   |

---

## 📈 Insights Gained

- Full-Time employees dominate the tech job market.
- Senior professionals earn the highest, especially in roles like AI Scientist or Data Architect.
- The United States, Great Britain, and India are top contributors in the dataset.
- Salary distribution varies significantly based on geography and company size.

---

## 🔧 Future Enhancements

- Add time trend analysis (Year-over-Year salary growth).
- Include gender or education-level analysis (if data available).
- Integrate real-time salary APIs for live data updates.
- Add filter for remote vs on-site jobs.

---



## 🙏 Acknowledgments

- Kaggle / AI Salary Survey (assumed data source)
- Tableau Public
- Mapbox for geospatial mapping

---


