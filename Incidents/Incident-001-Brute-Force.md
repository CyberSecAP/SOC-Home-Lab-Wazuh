# Incident 001 - Brute Force Login Attempt Detection

## Overview

A simulated brute force login attempt was performed against a Windows endpoint connected to the Wazuh SIEM environment.

The goal was to detect repeated failed authentication attempts and investigate the generated security alerts.

---

## Environment

SIEM:
- Wazuh

Endpoint:
- Windows Machine (Wazuh Agent)

Manager:
- Ubuntu Linux (Virtual Machine)

---

## Detection

Alert Type:
Windows Authentication Failure

Event Source:
Windows Security Logs

Detection Method:
Wazuh SIEM Rules

Severity:
High

---

## Investigation

The alert was reviewed in the Wazuh Dashboard.

The following information was analyzed:

- Event timestamp
- Username involved
- Number of failed attempts
- Windows event ID
- Source endpoint
- Rule ID

---

## Findings

Multiple failed login attempts were detected within a short time period.

This behavior matches characteristics of a possible brute force attack.

The activity was generated intentionally for security testing purposes.

---

## Response Actions

Recommended actions:

- Enable account lockout policies
- Monitor repeated authentication failures
- Investigate source of login attempts
- Review user account activity

---

## Conclusion

The Wazuh SIEM successfully detected and reported the simulated brute force activity.

This investigation demonstrates endpoint monitoring, alert triage, and basic incident response workflow.

---

Status:
Closed
