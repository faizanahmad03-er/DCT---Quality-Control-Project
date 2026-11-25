# DCT-01: Design and Development of a Risk-Based Quality Management and Quality Control Framework for a Digital Clinical Thermometer

## Project Overview

This project focuses on developing a structured Quality Management and Quality Control framework for a hypothetical Digital Clinical Thermometer (DCT-01).

The objective is to demonstrate how quality engineering principles can be applied throughout the conceptual product lifecycle of a medical device, covering product requirements, quality planning, inspection procedures, testing protocols, quality data analysis, defect investigation, Root Cause Analysis (RCA), Corrective and Preventive Action (CAPA), and risk management.

The project is organised into four weeks, comprising 25 documentation deliverables.

## Product Description

DCT-01 is a conceptual, battery-operated electronic contact thermometer designed for body temperature measurement through oral and axillary measurement modes.

**Proposed product components:**
- Temperature sensor (thermistor)
- Signal conditioning and processing electronics
- Microcontroller and firmware
- LCD display
- Battery
- Product enclosure

**Proposed product functions:**
- Temperature measurement and display in °C
- Battery status indication
- Device status and fault indication
- Informational temperature alert

Oral and axillary measurement modes are considered separately. The project does not assume an unvalidated conversion between the two measurement sites. The temperature alert is informational and is not intended to provide a medical diagnosis.

## Project Scope and Limitations

This is a documentation-based academic portfolio project.

- No physical prototype has been developed.
- No actual manufacturing or assembly has been performed.
- No physical laboratory testing or clinical testing has been conducted.
- All test execution records, observations, and numerical results are simulated for demonstration purposes.
- No product certification, regulatory approval, or independent conformity assessment has been obtained.
- The project does not claim conformity with any ISO, IEC, or regulatory standard.

Any provisional product requirements, acceptance criteria, risk scores, and test limits are academic project assumptions. They would require technical justification and approval before being used in an actual product-development or manufacturing environment.

---

## Project Structure and Deliverables

### Week 1 – Quality Planning

| No. | Deliverable | Description |
|---|---|---|
| 01 | Product Definition and Project Charter | Defines the product concept, intended use, project objectives, scope, and responsibilities. |
| 02 | Product Requirements Specification (PRS) | Establishes preliminary product requirements based on identified user needs. |
| 03 | Quality Control Plan (QCP) | Defines proposed quality control activities and inspection points throughout the manufacturing process. |
| 04 | Manufacturing Process Flowchart | Illustrates the proposed manufacturing, inspection, verification, and release workflow. |
| 05 | Process FMEA | Identifies potential process failure modes, evaluates illustrative risks, and proposes control measures. |
| 06 | Standards and Regulatory Applicability Matrix | Identifies relevant medical-device standards and Indian regulatory requirements for further applicability assessment. |

### Week 2 – Testing and Execution

| No. | Deliverable | Description |
|---|---|---|
| 07 | Quality Testing Master Plan | Establishes the overall testing approach, test programme, traceability, and documentation requirements. |
| 08 | Incoming Inspection Test Procedures | Defines proposed inspection procedures for incoming components and supplier documentation. |
| 09 | In-Process Inspection Procedures | Establishes inspection activities during the proposed assembly process. |
| 10 | Firmware and Functional Test Protocol | Defines proposed firmware verification and functional testing procedures. |
| 11 | Temperature Performance Test Protocol | Establishes a proposed method for evaluating temperature indication performance and repeatability using a suitable calibrated reference instrument. |
| 12 | Battery, Display and Fault Test Protocol | Defines proposed checks for battery operation, display functionality, and fault/status indication. |
| 13 | Final Inspection and Release Checklist | Provides a checklist for final product inspection, documentation review, and disposition. |
| 14 | Simulated Test Execution Records | Contains simulated test records demonstrating inspection tracking, test execution status, and nonconformity documentation. |

### Week 3 – Data Analysis and Reporting

| No. | Deliverable | Description |
|---|---|---|
| 15 | Test Results Analysis Report | Analyses the simulated test execution records and identifies quality gaps and blocked activities. |
| 16 | Quality Metrics Dashboard | Presents key quality metrics and workstream performance through an Excel-based dashboard. |
| 17 | Defect and Nonconformity Analysis | Documents the simulated defect, defect classification, Pareto analysis, and NCR investigation status. |
| 18 | Temperature Performance Analysis | Analyses simulated temperature comparison results and repeatability data, separately for oral and axillary measurements. |
| 19 | Week 3 Quality Analysis Report | Consolidates the quality metrics, defect analysis, temperature analysis, findings, and recommendations. |

### Week 4 – Root Cause Analysis and CAPA

| No. | Deliverable | Description |
|---|---|---|
| 20 | Root Cause Analysis Plan and Procedure | Establishes a structured procedure for nonconformity investigation and root cause determination. |
| 21 | Root Cause Investigation – SIM-NCR-001 | Documents the investigation of the simulated display-segment nonconformity using Fishbone and 5 Whys approaches. |
| 22 | CAPA Plan and Action Register | Tracks investigation follow-up actions, verification requirements, and effectiveness-review status. |
| 23 | CAPA Verification and Effectiveness Review | Defines the process for verifying corrective-action implementation and evaluating effectiveness. |
| 24 | Risk Management and PFMEA Update | Updates the process risk register to reflect the simulated display nonconformity and investigation status. |
| 25 | Week 4 RCA and CAPA Summary Report | Consolidates the investigation findings, action status, verification planning, and risk-management updates. |

---

## Key Project Findings

### 1. Simulated Test Execution Summary

The simulated test execution workbook contains 38 records.

| Test Status | Number of Records | Percentage |
|---|---:|---:|
| Simulated Pass | 17 | 44.7% |
| Simulated Fail | 1 | 2.6% |
| Blocked / TBD | 20 | 52.6% |
| **Total** | **38** | **100%** |

The high number of blocked activities highlights the importance of establishing approved product specifications, component details, firmware baselines, acceptance criteria, and test methods before conducting actual verification.

These figures represent only the constructed simulated dataset and must not be interpreted as actual product performance or manufacturing-quality results.

### 2. Defect and Nonconformity Analysis

One simulated display-related nonconformity was introduced into the test dataset.

- **NCR Reference:** SIM-NCR-001
- **Test Reference:** DT-02
- **Execution Record:** SIM-REC-032
- **Simulated Observation:** All mock display segments respond except the decimal-point segment.

The issue was carried forward into the Root Cause Analysis and CAPA documentation.

**Investigation status:** Root cause not established.

Potential causes involving the LCD, PCB interface, firmware display mapping, and test setup were identified as investigation hypotheses only. No cause was confirmed or ruled out.

The hypothetical unit remains on HOLD within the simulated scenario. No physical product defect or actual containment activity is claimed.

### 3. Temperature Performance Analysis

The simulated temperature dataset demonstrates the calculation and documentation of indication error and repeatability.

**Oral measurement examples:**
- Reference temperature: 37.0 °C; simulated indication: 37.1 °C; error: +0.1 °C.
- Reference temperature: 39.0 °C; simulated indication: 38.8 °C; error: −0.2 °C.

**Axillary measurement example:**
- Reference temperature: 37.0 °C; simulated indication: 36.9 °C; error: −0.1 °C.

**Repeatability example:**
- Number of simulated readings: 10
- Mean: 37.00 °C
- Range: 0.2 °C
- Sample standard deviation: approximately 0.067 °C

These are illustrative calculations based on simulated data. They do not establish actual measurement accuracy, clinical performance, or clinical validation.

### 4. RCA and CAPA Status

The Week 4 investigation carried the simulated display issue through the RCA and CAPA documentation workflow.

The final status is:

- NCR status: OPEN – Simulated
- Root cause: NOT ESTABLISHED
- Corrective action: NOT ASSIGNED / NOT IMPLEMENTED
- Implementation verification: NOT APPLICABLE AT PRESENT
- Effectiveness review: NOT EVALUATED
- Risk reduction: NOT DEMONSTRATED
- CAPA closure: NOT ELIGIBLE

The actions documented in the CAPA register are investigation and evidence-gathering follow-ups. They are not represented as implemented corrective actions.

---

## Quality Engineering Concepts Demonstrated

This project demonstrates the application and documentation of the following quality engineering concepts:

- Product definition and requirements planning
- Quality Control Plan development
- Manufacturing process mapping
- Incoming and in-process quality inspection
- Process Failure Mode and Effects Analysis (PFMEA)
- Standards and regulatory applicability assessment
- Test planning and test protocol development
- Firmware and functional verification planning
- Temperature performance and repeatability analysis
- Quality metrics and Excel dashboard development
- Defect classification and Pareto analysis
- Nonconformity reporting and investigation
- Root Cause Analysis using Fishbone and 5 Whys
- Corrective and Preventive Action (CAPA) planning
- CAPA verification and effectiveness review
- Risk register and PFMEA updates
- Technical documentation and quality reporting

## Standards and Regulatory References

The project includes an applicability assessment of relevant standards and regulatory frameworks, including:

- ISO 13485 – Medical devices Quality Management Systems
- ISO 14971 – Medical devices Risk Management
- ISO 80601-2-56 – Particular requirements for clinical thermometers
- IEC 60601-1 – Medical electrical equipment general safety requirements
- IEC 62366-1 – Usability engineering for medical devices
- ISO 10993-1 – Biological evaluation of medical devices
- ISO 20417 – Information supplied by the manufacturer
- India Medical Devices Rules, 2017

The inclusion of these references is for academic study and applicability assessment. It does not establish compliance or certification. The current editions, regulatory classification, and applicability must be verified against the final product design and intended use.

## Tools and Documentation

- Microsoft Word – Quality documentation, procedures, protocols, and reports
- Microsoft Excel – PFMEA, inspection records, simulated test data, quality metrics, dashboards, and CAPA tracking
- GitHub – Project documentation storage and version-controlled portfolio presentation

## Project Outcome

The project was completed as a four-week documentation-based academic portfolio exercise covering 25 deliverables across Quality Planning, Testing and Execution, Data Analysis and Reporting, and Root Cause Analysis and CAPA.

It demonstrates a structured approach to developing quality documentation for a hypothetical medical-device product, maintaining traceability between requirements, inspection activities, test records, nonconformities, investigation actions, and risk updates.

The project is intended to demonstrate foundational knowledge of Quality Engineering, Quality Assurance, Quality Control, and medical-device quality documentation. It does not represent a physically developed, tested, validated, or certified medical device.

---

## Author

**Electronics and Communication Engineering (ECE) Student**

**Project:** Digital Clinical Thermometer – Quality Management and Quality Control Framework
