# CC105 - Linear Data Architecture Subsystem

**Student Name:** [EJ T. Garcia]  
**Student ID:** [425004065]  
**Course & Section:** BSIT - NTC_CC105 (Data Structures w/ Lab)  
**Instructor:** Prof. Darwin C. Vargas, MIT  
**Academic Year:** 2026–2027 (1st Semester)  

---

## Executive Summary
This project audits, tests, and refactors a legacy dynamic linear memory subsystem. By removing global state vulnerabilities, fixing memory leaks, enforcing boundary checks, and streamlining algorithms, the subsystem was refactored into an RAII-compliant C++ class suitable for Milestone 1 deployment.

---

## Project Structure
```text
CC105_WEEK5_LastName_FirstName/
├── Original_Code/
│   └── LegacyLinearSubsystem.cpp
├── Refactored_Code/
│   ├── DynamicArray.h
│   ├── DynamicArray.cpp
│   └── RefactoredLinearSubsystem.cpp
├── Testing/
│   ├── Baseline_UnitTest_Table.pdf
│   └── Final_Regression_Table.pdf
├── Peer_Audit/
│   ├── Peer_Audit_Checklist.pdf
│   └── Peer_Evaluation_Signed.pdf
├── Screenshots/
│   ├── 01_Legacy_Compilation_Errors.png
│   ├── 02_Refactored_Clean_Build.png
│   └── 03_Memory_Sanitizer_Output.png
├── Documentation/
│   ├── BigO_Complexity_Analysis.pdf
│   ├── Refactoring_Documentation.pdf
│   └── Guide_and_Reflection_Answers.pdf
└── README.md


