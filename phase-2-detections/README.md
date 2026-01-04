\# Phase 2 – Detection Engineering



\## Objective

Design and implement detection rules using Windows event logs in Splunk to identify suspicious activity.



\## Detections Implemented

\### 1. Brute Force Login Detection

\- Detects repeated failed login attempts

\- Uses Windows Security Event ID 4625

\- Helps identify possible brute-force attacks



\## Data Sources

\- Windows Security Event Logs

\- Collected via Splunk Universal Forwarder



\## Status

\- Detection validated with real failed login attempts

\- Detection saved as a Splunk report

\- Screenshots and SPL queries documented



\## Next Steps

\- Convert detections into alerts

\- Add severity and response guidance

\- Create SOC-style dashboards



