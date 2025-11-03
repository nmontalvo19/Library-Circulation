# DS340-Project-2-Library-Circulation
Template for DS-340 Project 2: Library Circulation Analytics (SQLite + dbdiagram + CSV)
project2-library-circulation-analytics/

# 📚 Project 2 — Library Circulation Analytics

**Course:** DS-340 SQL Programming  
**Instructor:** Professor Natasha Montalvo  
**Student:** LASTNAME, FIRSTNAME  
**Semester:** Fall 2025  
**Due Date:** October 31, 2025  

---

## 🧭 Project Overview
This project simulates a **library circulation system**. You will design a relational database, populate it with realistic sample data, and analyze library activity using SQL.  
Each week builds upon the last — from the ERD to data quality checks and performance optimization.  
All tools are **free and Chromebook-friendly**.

**Tools Used:**
- [dbdiagram.io](https://dbdiagram.io) — ERD design  
- [SQLite Online](https://sqliteonline.com) — schema + queries  
- **Google Sheets** — sample data generation (export as CSV)  
- **GitHub** — project organization  
- **Blackboard** — final submission

---

## 📅 Project Timeline

| **Week** | **Focus** | **Deliverables** |
|-----------|------------|------------------|
| Week 1 | ERD Modeling | ERD.png + dbdiagram.io link |
| Week 2 | Schema Creation | `library_schema.sql` |
| Week 3 | Sample Data | CSVs + import screenshots |
| Week 4 | Initial Reports | Queries #1 – #8 (`reports.sql`) |
| Week 5 | Final Reports + Views | Queries #9 – #15 + `views.sql` |
| Week 6 | Data Quality & Performance | `dq_checks.sql` + `performance.md` |
| Week 7 | Final Submission | Complete folder + `README.md` |

---

## 🧩 Repository Structure

```text
project2_lastname_firstname/
├── README.md
├── ERD/
│   ├── ERD.png
│   └── ERD_link.txt
├── schema/
│   └── library_schema.sql
├── data/
│   ├── authors.csv
│   ├── books.csv
│   ├── patrons.csv
│   ├── copies.csv
│   ├── loans.csv
│   ├── fines.csv
│   └── import_screenshots/
│       ├── authors_import.png
│       ├── books_import.png
│       └── patrons_import.png
├── reports/
│   ├── reports.sql
│   ├── views.sql
│   └── dq_checks.sql
├── performance/
│   ├── performance.md
│   └── explain_before_after.png
└── docs/
    └── instructions.md
