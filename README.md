
# Shift Scheduler

A complete **Shift Scheduling System** designed to manage employee work schedules efficiently, ensuring fair distribution of shifts, compliance with working hours, and easy visualization of workforce allocation.

This project demonstrates the integration of **Python, MySQL, and Power BI** into a real-world scenario - from database creation and backend automation to visualization and insights - ideal for showcasing data engineering and analytics skills.

---

## Project Overview

**Shift Scheduler** is an end-to-end project that automates the scheduling process for employees. It allows managers to:
- Create and manage employee records
- Automatically schedule 8-hour shifts with a 5-day work week policy
- Assign employees to shifts with conflict checks
- Export weekly rosters for analysis and reporting
- Visualize workforce distribution and trends in Power BI

---

## Tech Stack

- **Python** - Backend scripting and data automation  
- **MySQL** - Database for storing employees, shifts, and assignments  
- **Jupyter Notebook** - Development and execution environment  
- **Power BI** - Interactive visualization and reporting  
- **CSV Export** - For data transfer between backend and BI tools  

---

## Features Implemented

- **Database Automation:** Creates database and tables directly from Python (no manual steps).  
- **Shift Management:** Generates shifts with enforced 8-hour durations and 5-day work week limit.  
- **Employee Assignment:** Automatically checks for scheduling conflicts and weekly limits.  
- **Roster Export:** Exports weekly schedules into CSV for analysis.  
- **Visualization Ready:** Data model optimized for Power BI dashboards.  

---

## Project Structure

```
Shift-Scheduler/

 shift_scheduler.ipynb      # Jupyter Notebook containing full project code
 roster_all_weeks.csv       # Weekly roster exported from database
 README.md                  # Project documentation (this file)
 Shift_Scheduler.pbix       # Power BI report file (optional)
```

---

## How It Works

1. **Database Setup:**  
   - Automatically creates `MCD_scheduler` database and required tables for employees, shifts, and assignments.

2. **Data Insertion:**  
   - Inserts employee details and auto-generates shifts between `2025-09-21` and `2025-10-11`.

3. **Scheduling Rules:**  
   - Each shift = 8 hours  
   - Maximum 5 shifts per employee per week  
   - No overlapping shifts allowed  

4. **Export Roster:**  
   - Weekly schedules exported to `roster_all_weeks.csv` for reporting and visualization.

5. **Power BI Visualization:**  
   - Import the CSV into Power BI and build dashboards showing weekly distribution, shift coverage, and workforce insights.

---

## Sample Visualizations

- **Weekly Shift Summary:** Employees scheduled per week  
- **Employee Utilization:** Distribution of total shifts per employee  
- **Shift Trends:** Role-based coverage and allocation over time  

---

## Getting Started

### Prerequisites

- Python 3.8+  
- MySQL Server  
- Jupyter Notebook  
- Power BI Desktop

### Setup Instructions

1. Clone the repository:  
   ```bash
   git clone https://github.com/rachelkarengutam-jpg/Shift-Scheduler.git
   cd Shift-Scheduler
   ```

2. Install required Python packages:  
   ```bash
   pip install mysql-connector-python pandas
   ```

3. Run the Jupyter Notebook to:  
   - Create the database and tables  
   - Insert data and generate shifts  
   - Export the roster CSV

4. Open Power BI and load the `roster_all_weeks.csv` to build dashboards.

---

## Future Enhancements

- Add a web-based UI for managing schedules  
- Automate weekly roster email notifications  
- Build advanced analytics dashboards with DAX

---

## Author

**Rachel Karen Gutam**  
London, UK  
[GitHub](https://github.com/rachelkarengutam-jpg)  

---

## Project Highlights

This project showcases skills in:
- Data Engineering  
- Database Management  
- Python Scripting  
- Business Intelligence & Reporting  

It’s a strong portfolio addition demonstrating the ability to **design, implement, and visualize a complete data-driven solution**.

---

© 2025 Rachel Karen Gutam. All Rights Reserved.