# SOC Analyst Portfolio

This portfolio contains hands-on SOC investigations I completed using Wazuh in my home lab. These labs focus on reviewing security alerts, analyzing Windows logs, and determining whether activity is malicious or benign.

## Skills Demonstrated

- SIEM monitoring with Wazuh
- Windows Event Log analysis
- Alert investigation
- PowerShell analysis
- MITRE ATT&CK
- Incident documentation

## SOC Investigations

### [Investigation #001](SOC%20Lab%20Investigation%201.pdf)
Windows authentication and failed login investigation.

### [Investigation #002](SOC%20Lab%20Investigation%202.pdf)
Investigation of multiple failed login attempts against a Windows user account.

### [Investigation #003 - PowerShell Process Discovery](SOC%20Lab%20Investigation%203.pdf)
Investigated a PowerShell Process Discovery alert, reviewed Event ID 4104, and analyzed surrounding activity to determine the alert was benign.

### [Investigation #004 – Suspicious Account Creation & Privilege Escalation](SOC%20Lab%20Investigation%204.pdf)

Investigated the creation of a new Windows account and identified that the account was added to the local Administrators group. Reviewed Windows Event IDs 4720 and 4732 and a Wazuh Level 12 alert to confirm the activity. Checked for successful logins, found none, and removed the test account after completing the investigation.
