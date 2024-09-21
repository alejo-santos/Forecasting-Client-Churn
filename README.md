# Forecasting-Client-Churn

Forecasting Client Churn for Interconnect

Overview

Interconnect, a leading telecom operator, aims to enhance its customer retention strategies by forecasting client churn. By identifying users who are likely to leave, Interconnect can proactively offer promotional codes and special plan options to retain them. To achieve this, the marketing team has gathered extensive data on their clientele, including personal information, plan details, and contract specifics.

Services Provided by Interconnect

Interconnect offers a range of services, primarily focusing on:

- **Landline Communication**: Multiple simultaneous connections.
- **Internet Services**: Available via DSL (Digital Subscriber Line) or fiber optic cable.

Additionally, Interconnect provides:

- **Internet Security**: Antivirus software (DeviceProtection) and a malicious website blocker (OnlineSafety).
- **Technical Support**: A dedicated support line (TechSupport).
- **Cloud Services**: File storage and data backup (OnlineBackup).
- **Entertainment**: TV streaming (StreamingTV) and a movie directory (StreamingMovies).

Clients have the flexibility to choose between monthly payments or 1- or 2-year contracts, with various payment methods and electronic invoicing options.

Data Description

The dataset comprises several files sourced from different areas:

- **contract.csv**: Contract information.
- **personal.csv**: Client personal data.
- **internet.csv**: Internet service details.
- **phone.csv**: Telephone service details.

Each file includes a `customerID` column, providing a unique identifier for each client. The contract data is current as of February.

Project Goals and Metrics

The primary goal is to predict client churn, with the target feature being the `end_date` column marked as ‘No’. The main evaluation metric is AUC-ROC, with accuracy as an additional metric.
