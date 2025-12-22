\# SIEM-Based Intrusion Detection System



This project implements a SIEM-based Intrusion Detection System using

Windows Sysmon and Splunk Enterprise.



\## Phase 1: Environment Setup



\### Objective

To build a reliable endpoint log collection pipeline for detection engineering.



\### Tools Used

\- Windows 10

\- Sysmon (Microsoft Sysinternals)

\- Splunk Enterprise

\- Splunk Universal Forwarder



\### Implementation

\- Installed and configured Sysmon for endpoint telemetry

\- Forwarded Windows Event Logs to Splunk using Universal Forwarder

\- Verified ingestion and indexing of Sysmon events

\- Resolved driver, authentication, and indexing issues



\### Outcome

\- Sysmon Event ID 1 logs successfully indexed in Splunk

\- Environment ready for detection engineering



Status: ✅ Phase 1 Completed



