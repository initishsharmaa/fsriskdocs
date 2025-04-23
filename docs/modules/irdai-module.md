---
sidebar_position: 8
---

# IRDAI Module

The IRDAI Module in Athena Guard is an intuitive page designed to help the insurance companies compy with the regulatory framework set by the Insurance Regulatory and Development Authority of India (IRDAI). This module ensures that every guideline, circular, and regulation is meticulously tracked, implemented, tested, and documented for internal governance and audit purposes.

## Key Features

### IRDAI Regulations
This is the central library capturing IRDAI Circulars, Product Guidelines, and Health Insurance Regulations.
- It is similar to the compliance module with the difference of the regulator being IRDAI.
- It seamlessly integrates compliance data entry, control validation, test execution, and risk scoring, making it user-friendly while supporting rigorous regulatory compliance efforts.
- Key regulatory extracts are visible at a glance and are tied to specific SOPs or policies in your business.

### Applicability & Policy Mapping
The regulatory extracts are segregated according each section in the regualtions and the users decide the applicability and map the organizations policies/SOPs to the relevant extracts.

**Control Documentation & Procedures :** The User Maps out control mechanisms established for each applicable regulation.
- The level of Documentation (Adequate/Inadequate)
- Peroidicity of the regulation (Ongoing/ Event Based)
- Types of Control(Automated, Semi- Automated and Manual)

**Test Execution & Evidence:** This Section tracks the test steps for control validation and stores supporting evidence with the responsible owners and units.

**Map Status:** The Map status (Open/Closed) with the timelines to be maintained for each regulatory extract.

### Risk and Complaince Scoring
Applies a weighted scoring system to assess control maturity and complaince risk.
The fields used for calculation of the Final Risk Score are 
- Documentation of Control (m)
- Automation Level (n)
- Compliance Score (Y)
- Final Risk Score = X × Y = m × n × Compliance Score
The Final Risk Score gives a Quantifiable metric to assess the risk and priortize the tasks accordingly.

### Download Data Feature 
- The Download excel feature in IRDAI module downloads the entire repository in the excel format for in-depth analysis and maintianing records.

## Use Cases

**Scenario:** IRDAI releases a circular requiring technological treatments to be included in health policies.
- The team updates the circular details in the module.
- The product team aligns SOPs and updates controls.
- A test is conducted with supporting evidence.
- Compliance is marked, risk score is calculated, and the record is ready for audits.


---
The IRDAI module in Athena Guard is an assistant in turning complex compliance mandates into clear, actionable tasks with timplines and proper testing validations.
