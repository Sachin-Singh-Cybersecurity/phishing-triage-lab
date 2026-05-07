# Investigation Notes

## Suspicious Indicators
- Misspelled domains
- Urgent language
- Suspicious links
- Unexpected attachments

## Analyst Goal
Identify potentially malicious emails before users interact with them.

## Suspicious Indicators Identified

### Domain Impersonation
Several emails used deceptive domains designed to imitate trusted brands.

Examples:
- paypaI.com
- micros0ft-support.com
- arnazon-security.net

Observation:
Attackers commonly replace letters with visually similar characters to trick users into trusting the sender.

---

## Urgency-Based Social Engineering

Multiple suspicious emails contained urgent language such as:
- "Reset Immediately"
- "Account Suspended"
- "Verify Within 24 Hours"

Observation:
Urgency tactics are frequently used in phishing campaigns to pressure users into acting without verification.

---

## Attachment Analysis

Some suspicious emails included attachments unexpectedly.

Potential Risks:
- Malware delivery
- Credential theft
- Malicious macros

Observation:
Unexpected attachments significantly increase phishing risk levels.

---

## High Risk Email Findings

### Case 1
Sender:
security-update@paypaI.com

Indicators:
- Impersonated domain
- Urgent password reset request
- Suspicious external link
- Attachment included

Risk Assessment:
High Risk

Reason:
Multiple phishing indicators detected simultaneously, increasing probability of credential theft attempt.

---

### Case 2
Sender:
support-team@micros0ft-help.com

Indicators:
- Fake Microsoft-style domain
- Security warning language
- External verification link

Risk Assessment:
Medium to High Risk

---

## Analyst Conclusion

Initial triage identified multiple emails exhibiting characteristics commonly associated with phishing attacks.

Key indicators included:
- domain impersonation
- urgency-based manipulation
- suspicious links
- unexpected attachments

Further improvements can include:
- automated threat scoring
- URL reputation checks
- attachment hashing
- sender reputation analysis

## Threat Pattern Analysis

Repeated phishing characteristics identified:
- impersonated domains
- urgency-driven language
- suspicious attachments

Most frequent attack method:
Domain impersonation combined with password reset requests.

---

## Escalation Logic

Emails with multiple phishing indicators were automatically escalated for further investigation.

Escalation Conditions:
- suspicious domain
- urgent language
- attachment presence

---

## Operational Observations

High-risk emails consistently combined multiple social engineering techniques.

This suggests attackers attempt to increase success rates through urgency and trust impersonation simultaneously.