# README

## Malspam Campaign Targeting Latin America - August 19, 2024

This report delves into a sophisticated malspam campaign identified on August 19, 2024, targeting Latin American countries, with a significant emphasis on Brazil. The campaign leverages highly deceptive phishing emails designed to trick recipients into downloading a malicious MSI file. Upon execution, this file initiates a multi-stage infection process, including the deployment of a legitimate executable from Valve Corporation alongside a malicious DLL. This trojanized DLL employs DLL side-loading techniques to bypass standard security defenses.

### Key Findings
- **Information Theft**: The malicious DLL is designed to steal browser-stored credentials and banking information, including through fake login windows mimicking prominent Brazilian banks.
- **Persistence Mechanisms**: The threat hides within the system as an inconspicuous file and manipulates the Windows registry for long-term persistence.
- **Advanced Capabilities**: Activities include keylogging, encrypted data exfiltration to a Command-and-Control (C2) server, arbitrary code execution, and manipulation of system settings.
- **System Reconnaissance**: The threat gathers comprehensive system details, including filesystem information and installed programs, using MSI queries and Windows APIs.
- **Rushed Development**: The code contains inefficiencies and duplicated logic, suggesting rapid deployment over quality, offering potential detection opportunities.

### Threat Impact
Despite its developmental shortcomings, this campaign represents a significant threat due to its advanced mechanisms for stealing sensitive information and evading detection. With a focus on Latin America and Brazil, it highlights the importance of robust cybersecurity measures to counter increasingly targeted and sophisticated attacks.

For further details, please refer to the full analysis in the attached report.
