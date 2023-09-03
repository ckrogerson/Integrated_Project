# Integrated_Project

## Table of Contents
1. [Deliverables](#deliverables)
2. [Repository Files](#files)
3. [Cleaned Insurance Data](#clean)
4. [Insurance Claims Notebook](#notebook)
5. [Advanced Features Insurance Data](#features)
6. [PowerBI Dashboard](#power)
7. [Business Presentation](#presentation)

<a name="deliverables"></a>
## 1. Deliverables

There are six major deliverables to be completed for the integrated project.

These include:
- Problem Landscape
- Project Board
- Jupyter Notebook for EDA and Feature Engineering
- Business Intelligence Dashboard
- Version Control
- Business Presentation 

<a name="files"></a>
## 2. Repository Files

Files included in this repository include the following:

- `Problem_Landscape.pdf`
- `Project_Board.JPG` (The project board was constructed and managed using Trello)
- `insurance_claims_raw.xlsx`
- `Cleaned_Insurance_Data.csv`
- `Insurance_Claims_Notebook.ipynb`
- `Advanced_Features_Insurance_Data.csv`
- `Insurance_Dashboard.pbix`
- `Insurance_Presentation.pdf`

Files requiring further context and explanation will be discussed below.

<a name="clean"></a>
## 3. Cleaned Insurance Data

The `Cleaned_Insurance_Data` file contains the insurance dataset after undergoing a thorough data cleaning process. 

This process involved handling missing values, through imputation, and addressing inconsistencies in the original data. 

2.1% of the entries in the dataset were found to include missing values across various features. All alterations made to the original dataset were tracked and can be found in the `insurance_claims_raw.xlsx` excel file in the "Tracking Changes" sheet.

The cleaned dataset was essential for conducting a more accurate analysis (considering the limited number of observations available).

<a name="notebook"></a>
## 4. Insurance Claims Notebook

The `Insurance_Claims_Notebook` is a comprehensive Jupyter Notebook developed in Python that showcases the exploratory data analysis (EDA) and feature engineering process. It includes code and explanations for rudimentary statistical analysis, generating data visualisations and the creation of advanced features. This notebook serves as a valuable resource for understanding the data exploration journey and the decisions made to enhance the dataset for further business insights.

<a name="features"></a>
## 5. Advanced Features Insurance Data

The `Advanced_Features_Insurance_Data` file contains the output of the feature engineering process within the aforementioned notebook, which is the cleaned insurance dataset enriched with advanced features.

A few examples of the engineered features include:
- `Total Premiums Paid` (derived from `Policy Annual Premiums` and `Months as Customer`)
- `Net Value of Customer` (derived from `Total Claim Amount` and `Total Premiums Paid`)
- a variety of datetime based features

In total, 13 new features were added to the dataset thereby enhancing the ability to procure valuable insights from the insurance claims data.

<a name="power"></a>
## 6. PowerBI Dashboard

The `Insurance_Dashboard` file was constructed through Microsoft Power BI and provides an interactive and visual representation of the insights derived from the insurance data. This dashboard includes various visualisations, such as charts, cards and tables that summarise key trends, patterns, and metrics. It streamlines the exploration of the data and enables stakeholders to gain a comprehensive understanding of the data-driven insights extracted throughout the project lifespan.

<a name="presentation"></a>
## 7. Business Presentation

Last but not least the `Insurance Presentation` is a comprehensive slidedeck that summarizes the project's objectives, methodologies, findings, and recommendations. It serves as a bridge between the technical aspects of the project and the business stakeholders. The presentation highlights the significance of the analysis, showcases key insights, and discusses the implications for the insurance industry in an African context. It is a crucial tool for effectively communicating the project's value and outcomes to a non-technical audience.
