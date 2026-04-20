---
sidebar_position: 4
title: Bulk Upload 
---
---

## Overview

The Bulk Upload module helps you:

- Upload large amounts of location data at once
- Update existing location records
- Download existing location data
- Reduce manual errors using predefined sample files

:::important File Format Requirement
Only **CSV (.csv)** files are supported for bulk upload and update operations.
:::

---

## Important Instructions

Before preparing and uploading your file, please ensure the following:

- Read all instructions carefully before preparing data
- Always download and use the **sample CSV file**
- Ensure the uploaded file is in **CSV format**
- Validate all data before proceeding
- Incorrect data may cause partial or failed uploads

---

## Bulk Upload Form

The Bulk Upload form consists of the following fields:

---

### Type (Upload / Update)  

Select the type of action you want to perform:

- **Upload** – Add new location records
- **Update** – Modify existing location records

---

### Location Type (Zipcodes / Cities / Areas)  

Select the type of location data you want to manage:

- Zipcodes
- Cities
- Areas

:::note Location Type Matching
The selected **Location Type** must match the structure of the uploaded CSV file.
:::

---

### File  

Upload the CSV file containing the location data.

- Accepted format: `.csv`
- File must follow the sample file structure exactly


---

:::important City Dependency Rule
**Cities must be added before zipcodes.**  
Each zipcode is **mandatory linked to a city**, so the corresponding `city_id` must already exist in the system.
:::

---

### Action Buttons

| Button | Description |
|------|------------|
| **Submit** | Upload or update the location data |
| **Reset** | Clear all selected fields |

---

## Sample & Download Files

To help you prepare valid data, the system provides the following files:

---

### Zipcode Files

- **Zipcode Bulk Upload Sample File**
- **Zipcode Bulk Update Sample File**
- **Zipcode Bulk Download File**

---

### Area Files

- **Area Bulk Upload Sample File**
- **Area Bulk Update Sample File**

---

### City Files

- **Cities Bulk Upload Sample File**
- **Cities Bulk Update Sample File**

---

### Instructions File

- **Location Bulk Instructions File**

:::tip Best Practice
Always download the latest sample file before preparing your CSV to avoid column mismatch errors.
:::

---
