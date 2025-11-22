# 🩺 Project Title: Healthcare Appointment No-Shows  

### 📊 Objective  
Analyze patterns in patient appointment attendance to understand factors contributing to no-shows and suggest improvements.

---

### 🧹 Data Cleaning Steps  
- Removed duplicates and incomplete rows  
- Standardized column names (e.g., `AppointmentDate`, `Age`, `Gender`)  
- Converted timestamps to `datetime` format  
- Handled missing values for `Neighborhood` and `SMS_Reminder`  

---

### 🧮 Exploratory Data Analysis (EDA)  
- Calculated no-show rates by **age group, gender, and neighborhood**  
- Analyzed time trends (day of week and time of day)  
- Created bar charts and heatmaps to visualize attendance patterns  

---

### 📈 Key Visualizations  
| Visualization | Description |
|----------------|-------------|
| No-Show Rate by Age Group | Found younger patients had higher no-show rates |
| Attendance by Day of Week | Monday mornings showed lowest attendance |
| SMS Reminder Impact | Patients receiving reminders were 30% more likely to attend |

---

### 💡 Insights  
- Reminder messages improve attendance  
- Younger patients (<30) and early appointments show higher no-show rates  
- Evening appointments and SMS reminders reduce missed visits  

---

### 🧰 Tools & Technologies  
**Excel**, **Python (pandas, matplotlib)**, **Power BI**, **GitHub**

---

### 📁 Folder Contents  
| Folder | Description |
|---------|-------------|
| `data/` | Dataset files (CSV, XLSX) |
| `notebooks/` | Jupyter notebooks or Excel analysis files |
| `visuals/` | Dashboard screenshots, charts, and graphs |

---

### 📄 Dataset Source  
Kaggle: *Medical Appointment No Shows Dataset*  
[https://www.kaggle.com/joniarroba/noshowappointments](https://www.kaggle.com/joniarroba/noshowappointments)
