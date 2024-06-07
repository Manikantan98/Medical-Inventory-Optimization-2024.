# Medical Inventory Optimization

## Introduction
This project aims to tackle the rising bounce rate within a healthcare institution, which has been causing patient dissatisfaction. The primary aim is to decrease the bounce rate by a minimum of 30%, while also cutting down on inventory expenses and expecting a revenue boost of at least 20 lacs INR. Employing a Data Analytics Project Management Methodology, the project will work with a dataset comprising 14,218 rows and 14 columns, specifically targeting the Supply Chain Management sector.

Efficient management of medical inventory holds immense importance for healthcare facilities worldwide. Inaccurate forecasting of drug demand can lead to issues like stockouts, overstocking, and increased expenses, all of which directly impact patient care. By harnessing advanced machine learning models, the proposed system seeks to refine medical inventory management practices, aiming to enhance stock availability, reduce bounce rates, elevate customer satisfaction, and minimize wastage in inventory costs.

To address the challenge of bounce rates in a healthcare setting, it's vital to concentrate on website optimization and improving user experience. Factors such as mobile responsiveness, readability, and site speed play pivotal roles in engaging patients and mitigating bounce rates. Strategies such as enhancing readability, optimizing for mobile platforms, and ensuring clear calls to action can significantly enhance user experience and lower bounce rates on medical practice websites.

## Overall Design Strategy
To develop a comprehensive design strategy for medical inventory management, the project will focus on addressing the rising bounce rate within a healthcare institution, which has been impacting patient satisfaction negatively. The primary objective is to reduce the bounce rate by a minimum of 30%, while concurrently optimizing inventory expenses and anticipating a revenue increase of at least 20 lacs INR. By implementing a Data Analytics Project Management Methodology, the project will analyze a dataset comprising 14,218 rows and 14 columns, with a specific emphasis on the Supply Chain Management sector.

## Data Overview
The medical dataset comprises 14,218 records and includes essential columns that capture various aspects of pharmaceutical transactions, patient behavior, and inventory management. Here is an overview of the dataset:

- **Typeofsales**: Indicates the type of drug sale (sold or returned).
- **Patient_ID**: Unique identifier for patients.
- **Specialisation**: Name of the specialization (e.g., Cardiology).
- **Dept**: Pharmacy department related to the formulation.
- **Dateofbill**: Date of purchase of medicine.
- **Quantity**: Quantity of the drug purchased.
- **ReturnQuantity**: Quantity of drug returned by patients.
- **Final_Cost**: Final cost of the drug (including quantity).
- **Final_Sales**: Final sales amount of the drug.
- **RtnMRP**: Maximum Retail Price (MRP) of returned drugs.
- **Formulation**: Type of formulation.
- **DrugName**: Generic name of the drug.
- **SubCat**: Subcategory (Type) of the category of drugs.
- **SubCat1**: Subcategory (condition) of the category of drugs.

### Missing Values
The dataset contains missing values in several columns:
- **Formulation**: 4.59% missing values.
- **DrugName**: 11.73% missing values.
- **SubCat**: 11.73% missing values.
- **SubCat1**: 11.9% missing values.

Addressing these missing values through imputation or removal is crucial to ensure data integrity and reliability for subsequent data analysis processes.

## Users
Users of the visualization dashboard will be:

1. **Supply Chain Managers**: They can analyze trends in medication sales and returns to optimize inventory management, ensuring that there are adequate stocks of essential medications while minimizing wastage.
2. **Pharmacy Managers**: They can use the visualization to track sales and returns of different drug formulations and categories, helping them make informed decisions about procurement and pricing strategies.
3. **Specialists and Department Heads**: They can gain insights into the usage patterns of medications within their specialty or department, allowing them to tailor treatment plans and protocols accordingly.
4. **Patient Experience Managers**: They can monitor trends in patient visits and medication purchases to identify areas for improving patient satisfaction, such as reducing wait times or offering educational resources.
5. **Financial Analysts**: They can use the visualization to assess revenue generation and cost management within the pharmacy department, identifying opportunities for increasing profitability or reducing expenses.
6. **Quality Assurance Teams**: They can track medication returns and complaints to identify potential issues with product quality or patient safety, facilitating timely interventions and improvements.

Overall, the visualization of visitation data from this dataset can provide valuable insights for various stakeholders involved in healthcare delivery, supply chain management, financial planning, and quality assurance within the organization.

## Business Problem
Healthcare facilities are experiencing an increase in bounce rates, which translates to patient dissatisfaction and potential revenue loss.

## Business Objectives

### Primary Objective
- Reduce bounce rates by 30%, minimizing patient frustration and ensuring timely access to necessary medical resources.

### Secondary Objective
- Optimize inventory costs without compromising patient care. This includes reducing stockouts, minimizing waste from expired medications, and streamlining procurement processes.

## Success Criteria

### Business Success Criteria
- Reduce bounce rates by 30%.

### Economic Success Criteria
- Increase revenue by 20 lacs INR by reducing bounce rate-related losses.

## Insights

### Dataset
- **medical_dataset** (14,218 records)
- **Key Columns**: Typeofsales, Patient_ID, Specialisation, Dept, Dateofbill, Quantity, ReturnQuantity, Final_Cost, Final_Sales, RtnMRP, Formulation, DrugName, SubCat, SubCat1

### Data Analysis

#### Before Data Cleaning
- Identified missing values needing imputation or removal.

#### After Data Cleaning
- Improved data quality and accuracy.

## Visualization Techniques

- **Line Graph Decomposition**: Decomposes trends in bounce rates for a deeper understanding of underlying factors.
- **Tree Plot**: Visualizes the hierarchical structure of factors influencing bounce rates, highlighting the impact of different departments, specializations, or types of sales.
- **100% Stacked Plot**: Depicts the composition of bounce rates across various categories, enabling rapid identification of high-impact areas.
- **Donut Chart**: Provides a clear overview of the distribution of bounce rates by category.
- **Card Slicer**: Offers an interactive way to explore and filter data based on specific criteria, facilitating deeper investigation of trends.

## Conclusion
This project demonstrates the significant role data-driven decision-making plays in optimizing medical inventory management. By harnessing the power of data and visualization, we can significantly improve patient satisfaction, operational efficiency, and ultimately, healthcare facility revenue.

## Technologies Used

- **Programming Languages**: Python (Pandas, NumPy, SciPy)
- **Database**: SQL (MySQL)
- **Data Analysis Tools**: Excel
- **Data Visualization Tools**: Power BI

## Project Duration

- **Start Date**: February 15, 2024
- **End Date**: March 20, 2024
