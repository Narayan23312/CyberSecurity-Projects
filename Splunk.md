# Splunk Deployment & Windows Log Collection

## Objective
Deploy Splunk in a lab environment and collect security-relevant logs from a Windows virtual machine.

## Tools Used
- Splunk Enterprise
- Splunk Universal Forwarder
- Windows VM (Windows 10 / Windows Server)
- Linux VM (Splunk Server)
- VirtualBox / VMware

## Lab Setup
- Configured Splunk Enterprise on a Linux virtual machine
- Deployed a Windows virtual machine as a log source
- Installed and configured Splunk Universal Forwarder on Windows

## What I Did
- Installed and configured Splunk Enterprise
- Enabled receiving ports on the Splunk server
- Installed Splunk Universal Forwarder on the Windows VM
- Configured Windows Event Log inputs (Security, System, Application)
- Verified successful log forwarding to Splunk
- Ran SPL searches to validate incoming events

## Outcome / Results
- Successfully ingested Windows event logs into Splunk
- Confirmed real-time log forwarding from the Windows VM
- Observed authentication and system events within Splunk searches

## What I Learned
- Hands-on experience with SIEM architecture and log pipelines
- How Windows event logs support security monitoring and detection
- Practical understanding of forwarders and centralized logging

## Evidence
- Screenshots of Splunk dashboards showing Windows logs
- Forwarder status confirmation
- Sample SPL queries and results

---


