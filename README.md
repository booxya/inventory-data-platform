# Inventory Data Management & Reporting System

## Key Highlights
- End-to-end data transformation (Excel → relational database → reporting)
- Data cleaning and normalization of inconsistent source data
- Centralized data model for reporting and stakeholder visibility

## Overview
This project presents a structured data platform designed to centralize and organize information about reports, sources, issues, and releases.

The solution was built by transforming a previously unstructured Excel-based inventory into a clean, normalized relational database, and then developing a reporting layer for stakeholders using Power BI.

---

##  Business Problem

- Inventory data was stored in Excel and lacked structure and consistency  
- Data contained missing values, outdated records, and inconsistencies  
- No centralized system to track reports, sources, issues, and releases  
- Stakeholders had limited visibility and relied on manual data checks  

---

##  Solution

A full data transformation pipeline was implemented:

1. **Data cleaning and validation**
   - Removed outdated and incorrect records  
   - Filled missing values where possible  
   - Standardized inconsistent formats  

2. **Database design (MS Access)**
   - Built a relational data model from scratch  
   - Normalized data into multiple related tables  
   - Defined relationships between entities  

3. **Query layer**
   - Created SQL queries to join and transform data  
   - Ensured consistency across related datasets  

4. **Reporting layer (Power BI)**
   - Developed a stakeholder-facing dashboard  
   - Provided simplified, business-friendly insights
  
##  My Role

- Led data cleaning and validation process  
- Designed and built the relational database  
- Developed SQL queries for data transformation  
- Created Power BI dashboard for stakeholders  

---

##  Data Model

The database consists of multiple interconnected entities, including:

- Reports  
- Sources  
- Issue Tracker  
- Release Notes  
- Automation  
- Categories and mappings  
- Time dimensions (DayOfWeek, HourOfDay)  
- Frequency definitions  

The model follows a normalized relational structure, reducing redundancy and improving data consistency.

---

##  Data Processing Flow
Excel Inventory (raw, unstructured) -> 
Data Cleaning & Validation -> 
Relational Database (MS Access) -> 
SQL Queries & Data Transformation -> 
Power BI Dashboard (Stakeholder View)


---

## Reporting Layer (Power BI)

A stakeholder-focused dashboard was built to provide:

- Report ownership and responsibility  
- Update frequency and status  
- Number of sources per report  
- Issue tracking and root cause visibility  
- Release notes and change history  

The dashboard abstracts technical complexity and allows stakeholders to easily access relevant information.

---

## Technical Highlights

- Data cleaning and validation process  
- Relational database design  
- SQL query development  
- Data normalization  
- Integration with Power BI  
- Business-focused reporting layer  

---

## Business Impact

- Centralized and structured inventory system  
- Improved data quality and consistency  
- Reduced manual effort in tracking and reporting  
- Increased transparency for stakeholders  
- Enabled scalable and maintainable data management  

---

## Design Decisions

- Migrated from Excel to relational database to improve scalability  
- Normalized data to reduce redundancy and inconsistencies  
- Separated technical and business layers (database vs dashboard)  
- Designed stakeholder view to simplify access to key insights  

---

##  Future Improvements

- Automation of data updates  
- Integration with additional data sources  
- Enhanced monitoring and reporting  
- Further optimization of data model  

---

##  Disclaimer

This project is based on a real-world enterprise solution. All details have been generalized and no confidential data is included.

Author: Joanna Wasilenko
