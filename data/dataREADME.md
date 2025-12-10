# 📊 Project Data Dictionary and Privacy Notes

This directory contains the various data segments used in the "Optimizing Employee Welfare Schemes" project. The original data was collected via an anonymous employee survey (N=400).

---

### ⚠️ Privacy and Anonymization Note

To ensure compliance with data privacy standards and internal company guidelines, all Personal Identifiable Information (PII), including **actual employee names** and **genuine Employee IDs**, has been **ANONYMIZED** or replaced with index codes (e.g., `ONGCXXXX`). The data is intended for academic and portfolio purposes only.

### File Descriptions

| File Name | Description | Key Columns |
| :--- | :--- | :--- |
| `ONGC_Combined_Responses_400.xlsx - Master Sheet.csv` | **The complete, combined raw data set** from the survey. Contains all responses before being split into separate analysis segments. | `Timestamp`, `Age`, `Gender`, `Department`, `Service_Group`, `Cost_Benefit_Rating`, `Leaving_Risk_Band`|
| `ONGC_Combined_Responses_400.xlsx - Demographic Insights.csv` | Contains employee attributes used for segmentation. | `Age_Group`, `Department`, `Designation`, `Marital Status` |
| `ONGC_Combined_Responses_400.xlsx - Performance Metrics.csv` | Data linking welfare schemes to employee performance/productivity self-assessments. | `Performance_Score`, `Productivity Index`, `Felt_More_Productive`|
| `ONGC_Combined_Responses_400.xlsx - Retention & Attrition.csv` | Data used to calculate the risk of employee turnover. | `Considered_Leaving`, `Influenced_To_Stay`, `Leaving_Risk_Band` |
| `ONGC_Combined_Responses_400.xlsx - Employee Feedback.csv` | Qualitative text responses on suggested improvements and additional comments. | `Suggestions`, `Other_Comments` |
| `ONGC_Combined_Responses_400.xlsx - Participation Rates .csv` | Binary flags (`0`/`1`) indicating usage of specific welfare schemes. | `Used_Housing`, `Used_Medical`, `Used_Canteen`, etc. |
| `ONGC_Combined_Responses_400.xlsx - Cost vs Benefit Analysis.csv` | Employee perception of the value derived from the schemes. | `Cost_Benefit_Rating`, `Cost_Benefit_Band`|
