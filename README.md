# Fleet Inventory Data Analysis (Excel)

Final project for the **IBM Data Analyst Professional Certificate** (Coursera), course *Excel for Data Analysis: Essential Skills & Techniques*.

## Scenario

As a junior data analyst in a local government office, I worked with a real-world fleet equipment inventory for Montgomery. The goal was to prepare the data for analysis and find out how equipment is distributed across departments and equipment classes.

## What I did

**Part 1: Data cleaning and preparation (Excel for the web)**
- Identified and fixed missing values, duplicate records, and inconsistent formatting

**Part 2: Analysis with pivot tables**
- Built pivot tables to count equipment by department and by equipment class
- Summarized the results for future dashboards and reporting

## Results

The summarized output in this repository covers **1,582 pieces of equipment** across **12 departments** and **14 equipment classes**.

- **Transportation** holds most of the fleet: 1,221 units, about 77% of the total. Its largest groups are transit buses (379), off-road vehicle equipment (276), and heavy-duty vehicles (248).
- **Permitting Services** (109 units) and the **Sheriff's Office** (85 units) come next. The Sheriff's Office runs most of the public safety vehicles.
- Across all departments, the most common classes are transit buses (379), heavy-duty vehicles (290), and off-road vehicle equipment (283).

![Equipment count by department](images/by_department.png)

![Equipment count by class](images/by_class.png)

## Files

| File | Description |
|---|---|
| `data/fleet_inventory_by_department_class.csv` | Pivot table output: equipment count by department and equipment class |
| `images/by_department.png` | Chart of total equipment per department |
| `images/by_class.png` | Chart of total equipment per class |

## Tools

Excel for the web: data cleaning, sorting and filtering, XLOOKUP/VLOOKUP, pivot tables, charts.
The charts in this README were generated from the exported pivot table output.

## Author

**Fritz Arnold Meno Njikam**, Data Analyst
[Portfolio](https://arnoldnjikam3173.github.io/arnold.njikam/) · [LinkedIn](https://www.linkedin.com/in/meno-njikam-arnold)
