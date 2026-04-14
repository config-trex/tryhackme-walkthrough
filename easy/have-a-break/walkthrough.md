# Room: Have A Break

## Objective
This room focuses on using OSINT, log analysis, and investigative techniques to investigate a corporate cargo theft and identify the likely insider threat.

## Skills Learned
- Email header analysis
- IP intelligence and attribution
- OSINT techniques
- Image and geolocation analysis
- Log correlation
- Timeline building

## Tools Used
- Email header analysis tools
- IP lookup tools
- OSINT resources
- Log review techniques

## Scenario Overview
This room simulates an investigation into a stolen shipment. Multiple artifacts are provided, such as an email, images, logs, and employee information. The goal is to review the evidence, connect the findings, and identify what happened.

## Phase 1: Email Analysis

### Actions Taken
- Reviewed the email artifact
- Examined header information
- Identified the originating infrastructure
- Used IP intelligence to gather context

### Findings
The email investigation provided a lead that helped narrow down the source of the communication and showed how attacker infrastructure can be hidden behind privacy-focused services.

### Takeaway
Email headers can provide important investigative clues even when the sender attempts to hide their location.

## Phase 2: Image and Location Analysis

### Actions Taken
- Reviewed the dashcam or image evidence
- Identified visible environmental clues
- Used location-based OSINT methods to narrow the area

### Findings
Visual details in the image helped reduce the search space and supported the larger investigation.

### Takeaway
Small image details can become strong evidence when combined with OSINT methods.

## Phase 3: Log Review and Insider Threat Analysis

### Actions Taken
- Reviewed available internal logs
- Looked for unusual access patterns
- Correlated activity with employee information

### Findings
The logs showed suspicious behavior that aligned with the incident timeline and supported an insider threat conclusion.

### Takeaway
Log correlation is critical when identifying malicious or unauthorized activity by internal users.


## MITRE ATT&CK Mapping
- T1078 - Valid Accounts
- T1082 - System Information Discovery
- T1046 - Network Service Discovery

## NIST Control Mapping
- AU-6 - Audit Review, Analysis, and Reporting
- AC-2 - Account Management
- SI-4 - System Monitoring

## Lessons Learned
- Email analysis can reveal useful attribution data
- OSINT can strengthen investigations
- Log review helps confirm suspicious behavior
- Multiple small clues can build a strong investigative picture

## Notes
This room is useful for building investigative and analytical thinking, especially for threat hunting, incident response, and insider threat analysis.
