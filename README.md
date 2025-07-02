# 🧠 Kickstarter Crowdfunding Data Analytics Project

## 📌 Overview

This project focuses on analyzing **Kickstarter crowdfunding data** to identify success patterns and provide actionable insights using tools like **Microsoft Excel, Power BI, MySQL, and Tableau**. The dataset includes project metadata, goal amounts, funding status, and user engagement statistics from various campaigns.

Our goal is to uncover the **success formula** behind crowdfunding projects and understand trends across different categories, time periods, and project features.

---

## 🎯 Objectives

* Crack the **success formula** for Kickstarter projects.
* Visualize **Key Performance Indicators (KPIs)** using BI tools.
* Understand how various features affect the likelihood of project success.
* Perform **ETL, Data Modeling, and Visualization** using multiple tools.
* Create dashboards and reports suitable for stakeholders.

---

## 🛠️ Tools & Technologies Used

* **Microsoft Excel** – Data exploration, pivot tables, dashboards.
* **Power BI** – Data modeling, DAX measures, dynamic reports.
* **Tableau** – Interactive dashboard building.
* **MySQL** – Query-based analysis and data processing.
* **Epoch Converter** – For converting timestamps to readable date formats.

---

## 📊 Key KPIs Tracked

1. **Projects Overview:**

   * Total Projects by Status (Successful, Failed, etc.)
   * Total Projects by Category and Location
   * Total Projects by Year, Quarter, and Month

2. **Successful Projects Insights:**

   * Total Amount Raised
   * Total Number of Backers
   * Average Duration of Successful Campaigns

3. **Top Successful Projects:**

   * By Number of Backers
   * By Amount Raised

4. **Success Percentage Metrics:**

   * Overall Success Percentage
   * Success % by Category, Year, Month
   * Success % by Goal Amount Ranges

---

## 🧮 Data Transformation & Modeling

1. **Epoch Time Conversion:**

   * Converted all `Created At`, `Launched At`, `Deadline`, and `Successful At` timestamps to human-readable dates using [EpochConverter](https://www.epochconverter.com/).

2. **Calendar Table Created:**
   Based on `Created Date`, we generated a calendar table with the following columns:

   * Year
   * Month Number
   * Month Name
   * Quarter (Q1–Q4)
   * Year-Month (e.g., 2022-Jan)
   * Weekday Number
   * Weekday Name
   * Financial Month (April = FM1 to March = FM12)
   * Financial Quarter (FQ1 to FQ4)

3. **Data Modeling:**

   * Built data models connecting:

     * `Projects`
     * `Category`
     * `Location`
     * `Creator`
   * Converted **Goal Amounts** into USD using a fixed exchange rate.

---

## 📌 Dataset Files Used

* `Crowdfunding_projects_1.xlsx`
* `crowdfunding_Category.xlsx`
* `Crowdfunding_Location.xlsx`
* `Crowdfunding_Creator.xlsx`

---

## 🔍 Insights & Findings

### ✅ Overall Success Rates

* Identified what percentage of total projects were successful across years, categories, and goal ranges.

### 🔝 Top Projects

* Ranked top projects by highest backer count and funds raised.

### 💰 Big Pledges

* Found that spotlighted projects (featured on Kickstarter) had:

  * \~40% of total projects
  * \~90% of total backers
  * \~90% of amount pledged
  * Over 200% goal achievement rate

---

## ⚠️ Challenges Faced

* Handling large data volumes across multiple Excel files.
* Dealing with uncleaned and unstandardized data.
* Converting Epoch timestamps into natural dates.
* Understanding Kickstarter-specific terminologies (e.g., `Blurb`, `Spotlight`, `Staff Pick`).

---


