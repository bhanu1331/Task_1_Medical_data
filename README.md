# Data Cleaning & Preprocessing – Medical Appointment No Shows

## 1. Objective
Clean and prepare the raw dataset for analysis by handling missing values, duplicates, inconsistent formats, and incorrect data types using Excel.

## 2. Tools Used
- Microsoft Excel

## 3. Dataset
- **Name:** Medical Appointment No Shows (Kaggle)
- **Rows:** 110,527 (before cleaning)
- **Columns:** 14
- **Description:** Contains patient appointment data including demographics, appointment dates, and whether patients showed up or not.

## 4. Steps Performed (Data Cleaning & Preprocessing)

1. **Handling Missing Values**
   - Identified missing values using Excel filters and conditional formatting
   - Filled or removed missing data depending on column context

2. **Removing Duplicates**
   - Checked for duplicate rows using Excel’s “Remove Duplicates”
   - Removed duplicates to ensure data accuracy

3. **Standardizing Text Values**
   - Standardized categorical columns like `Gender` 
   - Checked `No-show` column for consistent values 

4. **Date/Time Formatting**
   - Converted `ScheduledDay` and `AppointmentDay` to consistent date format (dd-mm-yyyy)

5. **Renaming Columns**
   - Removed spaces and made headers consistent (`PatientId`, `AppointmentDay`, `NoShow`)

6. **Data Type Correction**
   - Ensured numeric columns like `Age` are integer
   - Dates recognized as date objects

7. **Final Checks**
   - Verified no missing values remain in critical columns
   - Ensured no duplicate records
   - Checked that all categorical and numeric data are consistent

## 5. Summary of Changes
- Removed duplicate records
- Filled missing `Age` values with median
- Standardized `Gender` and `No-show` values
- Converted `ScheduledDay` and `AppointmentDay` to consistent date format
- Renamed columns to clean and uniform format

## 6. Key Learnings / Notes
- Handling missing values ensures accurate analysis of patient behavior
- Removing duplicates avoids inflated counts
- Standardizing categorical data improves reporting clarity
- Date formatting helps in calculating appointment gaps and trends


