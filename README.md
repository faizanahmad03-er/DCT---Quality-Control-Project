# DCT-01: Medical Device Quality Management Project

## Project Overview

**Project Title:** Design and Development of a Risk-Based Quality Management and Quality Control Framework for a Digital Clinical Thermometer

**Product Concept:** DCT-01, a hypothetical battery-operated electronic contact thermometer intended to measure body temperature at oral and axillary sites.

This project demonstrates how quality planning, product requirements, process controls, process-risk analysis, inspection procedures, testing protocols, and quality data analysis can be structured for a medical-device concept.

## Project Status and Limitations

This is an academic, documentation-based project. No physical prototype has been built, no manufacturing process has been operated, and no clinical testing, accredited laboratory testing, regulatory submission, certification, or regulatory approval has been completed.

Any example acceptance criteria, risk scores, test scenarios, process controls, and data used in this project are provisional or simulated unless explicitly stated otherwise. They must not be interpreted as verified product performance or evidence of compliance.

The project does not claim conformity with ISO 13485, ISO 14971, ISO 80601-2-56, IEC 60601-1, or any other standard. Standards and regulatory references are included for applicability assessment and further study only.

## Product Concept

- **Product Identifier:** DCT-01
- **Device Type:** Digital clinical thermometer
- **Measurement Sites:** Oral and axillary
- **Power:** Battery-operated
- **User Interface:** LCD with temperature and battery-status indication
- **Alert:** Informational temperature alert; not a diagnosis
- **Prototype Status:** Not built

Oral and axillary measurement modes are treated separately. No unvalidated conversion between measurement sites is assumed.

## Project Progress and Deliverables

### Week 1 – Quality Planning

The Week 1 folder contains six deliverables:

| No. | Deliverable | Purpose |
|---|---|---|
| 01 | Product Definition and Project Charter | Defines the product concept, intended use, scope, objectives, stakeholders, and project boundaries. |
| 02 | Product Requirements Specification (PRS) | Translates user needs into preliminary, measurable product requirements and verification approaches. |
| 03 | Quality Control Plan (QCP) | Defines proposed inspection and control activities across the conceptual manufacturing process. |
| 04 | Manufacturing Process Flowchart | Visualises the proposed manufacturing, inspection, release, and post-market feedback flow. |
| 05 | Process Failure Mode and Effects Analysis (PFMEA) | Identifies potential process failure modes, evaluates illustrative risk scores, and proposes risk-reduction actions. |
| 06 | Standards and Regulatory Applicability Matrix | Maps potentially relevant standards and Indian medical-device regulatory requirements to the project. |

### Week 2 – Testing and Execution

The Week 2 folder contains eight deliverables:

| No. | Deliverable | Purpose |
|---|---|---|
| 07 | Quality Testing Master Plan | Establishes the overall testing strategy, responsibilities, equipment controls, acceptance decisions, and test-record requirements. |
| 08 | Incoming Inspection Test Procedures | Defines inspection procedures for incoming components such as sensors, PCBs, LCDs, batteries, and enclosures. |
| 09 | In-Process Inspection Procedures | Defines inspection activities during the conceptual assembly and manufacturing process. |
| 10 | Firmware and Functional Test Protocol | Defines firmware verification and functional testing activities for the thermometer. |
| 11 | Temperature Performance Test Protocol | Defines bench verification approaches for indication error, repeatability, and response time. |
| 12 | Battery, Display and Fault Test Protocol | Defines battery-related, display-functionality, and fault-handling verification activities. |
| 13 | Final Inspection and Release Checklist | Consolidates final inspection, documentation review, nonconformity review, and proposed product disposition requirements. |
| 14 | Simulated Test Execution Records | Provides an Excel-based demonstration dataset containing simulated test outcomes, blocked tests, and a simulated nonconformity. |

**Important:** Step 14 contains simulated data only. It includes one deliberately introduced display-related failure to demonstrate nonconformity reporting and subsequent root-cause analysis. It does not represent an actual product defect or physical test result.

## Proposed Project Workflow

1. Define the product and intended use.
2. Establish preliminary product requirements.
3. Develop the quality control plan.
4. Map the conceptual manufacturing process.
5. Identify process risks using PFMEA.
6. Assess standards and regulatory applicability.
7. Develop quality testing plans and inspection procedures.
8. Establish firmware, functional, temperature, battery, display, and fault test protocols.
9. Prepare simulated test execution records.
10. Analyse quality data and identify trends.
11. Perform root cause analysis (RCA).
12. Develop corrective and preventive action (CAPA) proposals.
13. Establish verification and effectiveness-check approaches.

## Important Risk Management Note

The PFMEA is a process-risk analysis aid for this academic exercise. It does not replace a complete medical-device risk management file.

Risk Priority Number (RPN) is used as a prioritisation aid and is not the sole basis for risk acceptability. Risk-control effectiveness must be verified before residual risk is re-evaluated.

## Planned Project Phases

- **Week 3 – Data Analysis and Reporting:** Analysis of simulated inspection and test records, failure classification, quality metrics, and reporting.
- **Week 4 – Root Cause Analysis and CAPA:** Investigation of the simulated nonconformity, identification of potential root causes, corrective-action proposals, and effectiveness verification planning.
- **Final Project Portfolio:** Consolidation of project documentation, findings, limitations, and key quality-engineering learnings.

These phases are planned deliverables and should not be interpreted as completed work until their documentation is added to the repository.

## Repository Structure

```text
DCT---Quality-Control-Project/
│
├── README.md
│
├── Week 1 - Quality Planning/
│   ├── 01_Product_Definition_and_Project_Charter.docx
│   ├── 02_Product_Requirements_Specification_DCT-01.docx
│   ├── 03_Quality_Control_Plan_DCT-01.docx
│   ├── 04_Manufacturing_Process_Flowchart_DCT-01.png
│   ├── 05_Process_FMEA_DCT-01.xlsx
│   └── 06_Standards_and_Regulatory_Applicability_Matrix_DCT-01.docx
│
├── Week 2 - Testing and Execution/
│   ├── 07_Quality_Testing_Master_Plan_DCT-01.docx
│   ├── 08_Incoming_Inspection_Test_Procedures_DCT-01.docx
│   ├── 09_In_Process_Inspection_Procedures_DCT-01.docx
│   ├── 10_Firmware_and_Functional_Test_Protocol_DCT-01.docx
│   ├── 11_Temperature_Performance_Test_Protocol_DCT-01.docx
│   ├── 12_Battery_Display_and_Fault_Test_Protocol_DCT-01.docx
│   ├── 13_Final_Inspection_and_Release_Checklist_DCT-01.docx
│   └── 14_Simulated_Test_Execution_Records_DCT-01.xlsx
│
├── Week 3 - Data Analysis and Reporting/
│   └── Planned deliverables
│
├── Week 4 - Root Cause Analysis and CAPA/
│   └── Planned deliverables
│
└── Final Project Portfolio/
    └── Planned deliverables
```

*Note: Week 3, Week 4, and Final Project Portfolio are planned phases. Their folders and contents will be added as the project progresses.*

## Author

Engineering Student – Electronics and Communication Engineering

## Project Disclaimer

This repository is intended for academic learning and demonstration of quality-engineering principles in the context of a hypothetical medical device. It is not a validated medical-device technical file, manufacturing quality record, regulatory submission, or evidence of product certification or approval.
