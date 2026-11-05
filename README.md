# Windows Event Log Analysis

## Project Overview
This is a beginner-level SOC Analyst practical project focused on analysing Windows Security Event Logs using Windows Event Viewer.

The project examines two authentication-related events:
- **Event ID 4625:** Failed logon
- **Event ID 4624:** Successful logon

## Objectives
- Understand Windows Security Logs.
- Investigate failed and successful authentication events.
- Interpret Windows logon types and failure codes.
- Review process and network information.
- Document findings and security recommendations.

## Tools Used
- Windows Event Viewer
- Windows Security Logs

## Key Findings
- Examined a failed logon event (4625).
- Identified substatus `0xC000006A`, indicating an incorrect password.
- Examined a successful service logon event (4624).
- Identified `services.exe` as the process associated with the selected service logon.
- Source network addresses were unavailable in the examined records.
- No conclusion of malicious activity was made without sufficient evidence.

## Project Structure
```text
Windows-Event-Log-Analysis/
├── README.md
├── Report/
│   └── Windows_Event_Log_Report.pdf
├── Screenshots/
│   └── (Add your own screenshots if available)
└── Findings/
    └── Investigation_Findings.md
```

## Learning Outcomes
Through this project, I gained practical experience with Windows Event Viewer, Security Event IDs, authentication analysis, logon types, and basic security investigation documentation.

## Disclaimer
This project was conducted for educational purposes using selected Windows Security Log records from my own computer. Personal identifying information should be removed from public evidence.