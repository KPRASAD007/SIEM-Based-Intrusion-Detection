\# Phase 2 – Detection Planning



\## Objective

Design detection logic using Windows Security Event Logs to identify common intrusion techniques in a SOC environment.



---



\## Detection 1: Brute-Force Login Attempts

\- Event ID: 4625

\- Description: Multiple failed login attempts against the same account or from the same source.

\- Risk: Credential guessing and password attacks.

\- MITRE ATT\&CK: T1110 – Brute Force



---



\## Detection 2: Brute-Force Followed by Successful Login

\- Event IDs: 4625, 4624

\- Description: Multiple failed logins followed by a successful login within a short time window.

\- Risk: Compromised credentials.

\- MITRE ATT\&CK: T1110 – Brute Force



---



\## Detection 3: Account Lockout

\- Event ID: 4740

\- Description: Account locked due to repeated authentication failures.

\- Risk: Active attack against user accounts.

\- MITRE ATT\&CK: T1110 – Brute Force



---



\## Detection 4: Privileged Logon

\- Event ID: 4672

\- Description: Logon session assigned administrative privileges.

\- Risk: Privilege escalation or misuse of admin accounts.

\- MITRE ATT\&CK: T1078 – Valid Accounts



