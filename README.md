# 🏃 Fitbit Wellness Dashboard – Tableau

An interactive **Tableau dashboard** designed to analyze Fitbit user activity, fitness behavior, sleep quality, calories burned, and engagement patterns.

The project combines multiple Fitbit datasets to transform wellness and fitness data into meaningful visual insights that can help understand user activity levels, sleep behavior, and overall engagement.

---

## 📑 Table of Contents

* [📊 Project Overview](#-project-overview)
* [🎯 Project Objectives](#-project-objectives)
* [🛠️ Tools & Technologies](#️-tools--technologies)
* [📂 Dataset](#-dataset)
* [📊 Dashboard Overview](#-dashboard-overview)
* [📈 Key Visualizations](#-key-visualizations)
* [🔍 Key Insights](#-key-insights)
* [🎛️ Dashboard Features](#️-dashboard-features)
* [📁 Repository Structure](#-repository-structure)
* [🚀 How to Use](#-how-to-use)
* [👩‍💻 Skills Demonstrated](#-skills-demonstrated)
* [🏁 Conclusion](#-conclusion)

---

## 📊 Project Overview

**Fitbit Wellness Dashboard** is an interactive Tableau project created to analyze fitness and wellness data collected from Fitbit users.

The dashboard provides insights into:

* 🏃 Daily physical activity
* 👟 Average daily steps
* 🔥 Calories burned
* ⏱️ Active minutes
* 😴 Sleep quality
* 👨‍💼 Activity across different occupations
* 🏋️ Activity across fitness categories
* 📈 User engagement trends
* ❤️ Overall wellness behavior

The goal of the project is to turn raw Fitbit data into an interactive dashboard that makes it easier to identify patterns and compare wellness behavior across different user groups.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze Fitbit users' daily physical activity.
* Understand average daily step patterns.
* Compare activity levels across different user categories.
* Analyze activity levels across occupations.
* Study sleep quality across different occupations.
* Analyze user engagement by fitness category.
* Compare physical activity with calories burned.
* Identify declining, improving, and stable user engagement.
* Provide an interactive dashboard for wellness analysis.

---

## 🛠️ Tools & Technologies

| Tool / Technology      | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **Tableau**            | Dashboard development and data visualization |
| **Tableau Desktop**    | Dashboard and worksheet creation             |
| **Calculated Fields**  | KPI and analytical calculations              |
| **Data Visualization** | Charts and interactive analysis              |
| **CSV**                | Source datasets                              |
| **Data Analysis**      | Extracting fitness and wellness insights     |

---

## 📂 Dataset

The project uses multiple Fitbit datasets to analyze different aspects of user wellness.

### 📄 Datasets Included

* **Fitbit_Activities.csv** – Activity and fitness-related information
* **Fitbit_HR.csv** – Heart-rate data
* **Fitbit_Sleep.csv** – Sleep-related information
* **Fitbit_Steps.csv** – Daily step information
* **Fitbit_Users.csv** – User demographic and profile information

These datasets are combined and analyzed in Tableau to create the dashboard and its visualizations.

---

# 📊 Dashboard Overview

The main dashboard provides a centralized view of Fitbit user wellness and engagement.

### 📌 Key Performance Indicators

The dashboard includes the following KPIs:

* 👟 **Average Daily Steps:** 296.0
* 👥 **Total Users:** 424
* ⏱️ **Average Active Minutes:** 35.95
* 🔥 **Average Calories Burned:** 3.319

> KPI values are based on the current dataset and dashboard calculations.

### 🖼️ Dashboard Preview

![Fitbit Wellness Dashboard](fitness%20data/Screenshots%20uploaded/fitbit-wellness-dashboard.png)

---

# 📈 Key Visualizations

## 👟 1. Steps by Category

This visualization compares the average number of steps across different fitness categories.

### Categories analyzed include:

* Gym addict
* Active Millennial
* Fitness-conscious users
* Just an average Joe
* Casual exerciser
* Busy Mum

This helps identify which user categories demonstrate higher levels of physical activity.

---

## 👨‍💼 2. Occupation Activity

The dashboard compares average daily steps across different occupations.

### Occupations analyzed include:

* Builder
* Police force
* Recruiter
* Telesales person
* Tax inspector

This visualization helps explore whether occupation is associated with differences in physical activity.

---

## 😴 3. Quality of Sleep

The sleep-quality visualization compares sleep performance across different occupations.

It helps identify variations in sleep quality among different professional groups and provides an additional perspective on overall wellness.

---

## 📊 4. Engagement by Category

This visualization analyzes changes in user activity across different fitness categories.

The dashboard categorizes engagement into:

* 🔵 **Declining**
* 🟠 **Improving**
* 🟢 **Stable**

A **20% decline threshold** is also used to identify significant decreases in activity.

---

## 🔥 5. Calories and Activity Analysis

The dashboard also provides analysis related to calories burned and physical activity.

This helps understand how activity levels vary between different users and categories.

---

# 🔍 Key Insights

The dashboard helps identify several important patterns in Fitbit wellness data:

* 👟 Physical activity levels vary significantly across different fitness categories.
* 🏃 Some fitness categories demonstrate considerably higher average daily steps.
* 👨‍💼 Activity levels differ across occupations.
* 😴 Sleep quality varies between different occupational groups.
* 📈 User engagement can be classified into improving, stable, and declining segments.
* ⚠️ The 20% decline threshold helps identify users or categories experiencing significant reductions in activity.
* 🔥 Activity and calorie-related metrics provide additional indicators of user wellness.
* 📊 Combining activity, sleep, and engagement metrics provides a broader view of Fitbit user behavior.

---

# 🎛️ Dashboard Features

* 📊 Interactive Tableau dashboard
* 🎯 KPI cards
* 👟 Average daily step analysis
* 👨‍💼 Occupation-based analysis
* 😴 Sleep quality analysis
* 📈 Engagement analysis
* 🔥 Calories burned analysis
* 🔵 Declining engagement identification
* 🟠 Improving engagement identification
* 🟢 Stable engagement identification
* 🔄 Interactive filtering
* 📑 Multiple analytical worksheets
* 📱 Dashboard device preview
* 🎨 Professional dashboard design

---

# 📁 Repository Structure

```text
Fitbit-Wellness-Dashboard/
│
├── 📁 fitness data/
│   │
│   ├── 📁 Screenshots uploaded/
│   │   └── fitbit-wellness-dashboard.png
│   │
│   ├── 📄 Fitbit_Activities.csv
│   ├── 📄 Fitbit_HR.csv
│   ├── 📄 Fitbit_Sleep.csv
│   ├── 📄 Fitbit_Steps.csv
│   ├── 📄 Fitbit_Users.csv
│   │
│   ├── 📊 fitbitwellnessdashboard.twb
│   │
│   └── 📄 README.md
```

> **Note:** Update the screenshot filename in the README if you use a different filename.

---

# 🚀 How to Use

### 1️⃣ Download the Repository

Clone or download this repository to your local machine.

### 2️⃣ Open the Tableau Project

Open the `.twb` Tableau workbook using **Tableau Desktop**.

### 3️⃣ Connect the Dataset

Make sure the CSV files are available in the expected location.

If Tableau cannot locate the files, update the data source paths inside Tableau.

### 4️⃣ Explore the Dashboard

Use the dashboard filters and visualizations to explore:

* Fitness categories
* Occupations
* Activity levels
* Sleep quality
* User engagement
* Calories burned
* Daily steps

---

# 👩‍💻 Skills Demonstrated

**Tableau** • **Data Visualization** • **Data Analysis** • **Dashboard Development** • **Calculated Fields** • **KPI Development** • **Interactive Dashboards** • **Fitness Analytics** • **Data Storytelling** • **Business Intelligence**

---

# 📌 Project Highlights

> **424 Users • Activity Analysis • Sleep Analysis • Step Tracking • Calories Burned • Occupation Analysis • Engagement Analysis • Tableau Dashboard**

---

# 🏁 Conclusion

The **Fitbit Wellness Dashboard** demonstrates how Tableau can be used to transform raw fitness and wellness data into interactive and meaningful visual insights.

By combining **activity, steps, sleep, calories, occupation, and engagement data**, the dashboard provides a comprehensive view of user wellness behavior.

The project demonstrates practical skills in **data visualization, dashboard development, data analysis, KPI creation, and business intelligence using Tableau**.

---

## ⭐ Project Type

**Data Analytics | Business Intelligence | Tableau | Fitness & Wellness Analytics**
