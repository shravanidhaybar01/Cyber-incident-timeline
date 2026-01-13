# Incident 001 – Unauthorized Login Attempt

## Date
2026-01-12

## Incident Type
Unauthorized Access

## Description
Multiple failed login attempts were detected on a user account.
The attempts originated from an unknown IP address.

## ⏱ Incident Timeline
- *T0 – Initial Access:* Employee opened a phishing email attachment.
- *T1 – Execution:* Malware executed and established persistence.
- *T2 – Lateral Movement:* Malware spread to internal systems.
- *T3 – Impact:* Critical hospital systems encrypted.
- *T4 – Response:* IT team isolated affected systems and initiated recovery.

  ## 🔍 Detection Opportunities
- Email gateway alerts for malicious attachments
- Endpoint alerts for abnormal file encryption activity
- Network monitoring for unusual lateral movement
  
  ## 💥 Impact
- Disruption of hospital operations
- Temporary loss of access to patient data
- Increased operational and recovery costs

  ## Root Cause
Weak password and repeated login attempts from suspicious IP.

## Mitigation & Response
- Account lockout enabled
- Password reset completed
- Suspicious IP blocked

## Lessons Learned
- Enable MFA
- Improve login monitoring

