# Insurance Claim Data Analysis

## Overview

This repository contains the implementation of an end-to-end data analysis project on historical insurance claim data. The primary objective of this analysis is to optimize marketing strategies and identify “low-risk” customers who may qualify for reduced premiums, thereby attracting new clients. 

The dataset comprises detailed information about insurance policies, clients, vehicles, geographical regions, and claims data for the period from February 2014 to August 2015.

---

## Features

The project encompasses the following analyses:
1. **Data Cleaning and Preparation**:
   - Handling missing values.
   - Converting numerical fields with improper formatting.
   - Normalizing categorical and date fields for consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Summarization of numerical and categorical data.
   - Detection and treatment of outliers.
   - Correlation analysis to uncover relationships between variables.

3. **Insights and Trends**:
   - Geographical trends in `TotalPremium` and `TotalClaims`.
   - Monthly trends in premiums and claims.
   - Analysis of cover types and vehicle types.

4. **Visualization**:
   - Distribution plots for numerical features.
   - Heatmaps for correlation analysis.
   - Geographical and temporal visualizations for premium and claim trends.


## Dataset

The dataset includes 1,000,098 rows and 52 columns, with details structured as follows:

- **Insurance Policy Details**:
  - `UnderwrittenCoverID`, `PolicyID`, `CoverType`, `CalculatedPremiumPerTerm`, `TotalPremium`, `TotalClaims`, etc.

- **Client Demographics**:
  - `MaritalStatus`, `Gender`, `IsVATRegistered`, `Citizenship`, etc.

- **Vehicle Information**:
  - `VehicleType`, `RegistrationYear`, `make`, `Model`, `cubiccapacity`, `kilowatts`, etc.

- **Geographical Information**:
  - `Province`, `PostalCode`, `MainCrestaZone`, etc.

- **Temporal Data**:
  - `TransactionMonth`.

---

## Project Structure

```plaintext
.
├── data/                   # Contains raw and cleaned datasets
├── notebooks/              # Jupyter notebooks for EDA and analysis
├── README.md               # Project documentation
└── requirements.txt        # Dependencies for the project

## Installation and Usage

### **Requirements**

To run this project locally, ensure you have the following installed:
- Python 3.10 or higher
- Required Python libraries (see `requirements.txt`):
  - pandas
  - numpy
  - matplotlib
  - seaborn

### **Setup Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/SaraFedlu/Insurance-Data-Insights-and-Prediction.git
   cd Insurance-Data-Insights-and-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis:
   - Open and run the notebooks in the `notebooks/` folder.

---

## Key Insights

- **Outliers**: Significant outliers in `TotalPremium` and `TotalClaims` were identified, requiring special handling for analysis.
- **Geographical Trends**:
  - High premiums observed in provinces like KwaZulu-Natal.
  - Claims vary significantly between provinces, with Gauteng and KwaZulu-Natal showing higher averages.
- **Temporal Trends**:
  - An upward trend in premiums and claims, with a peak between late 2014 and early 2015.

---

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## Contact

For inquiries or collaboration opportunities, feel free to reach out:
- **Email**: sfedlu28@gmail.com
- **GitHub**: SaraFedlu(https://github.com/sarafedlu)
