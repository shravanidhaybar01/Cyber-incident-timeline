# Incident 001 – Unauthorized Login Attempt

## Date
2026-01-12

## Incident Type
Unauthorized Access

## Description
Multiple failed login attempts were detected on a user account.
The attempts originated from an unknown IP address. 

## Severity Level
Medium

## MITRE ATT&CK Mapping
- T1110 – Brute Force

## ⏱ Incident Timeline
- 10:02 AM – Authentication failure alerts triggered
- 10:05 AM – Account lockout policy activated
- 10:10 AM – SOC analyst reviewed logs
- 10:15 AM – User identity verified
- 10:20 AM – Password reset enforced

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
- 
## Prevention Measures
- Enable Multi-Factor Authentication (MFA)
- Implement IP-based rate limiting
- Strengthen password policy
- Continuous login monitoring

  ## Severity Justification
This incident was classified as *Medium* severity because:
- Unauthorized access attempts were detected
- No confirmed data breach occurred
- The incident was contained quickly

 ## Evidence / Logs (Simulated)
- Multiple failed login attempts from a single IP address
- Authentication failure alerts triggered
- Account lockout events recorded

 ## Post-Incident Review

### What Went Well
- Alerts triggered quickly
- Automated account lockout worked as expected

### What Could Be Improved
- Earlier detection of brute force patterns
- Stronger password enforcement

## Incident Status
Closed

## Lessons Learned
- Enable MFA
- Improve login monitoring

