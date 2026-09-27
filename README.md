# simple-wazuh-customRule

A custom Wazuh SIEM detection rule written in XML to detect defense evasion tactics on windows endpoints
Mechanism: monitors the win.system.eventID field for event ID 1102. when an attacker attempts to clear the windows security Log to cover their tracks, this rule triggers a "High Severity" alert
framework Mapping: mapped directly to MITRE ATT&CK Technique T1070.001 (Clear Windows Event Logs) and includes compliance tagging for PCI DSS and GDPR auditing
