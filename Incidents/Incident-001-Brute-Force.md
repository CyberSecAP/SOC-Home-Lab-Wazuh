# Incident 001 - Brute Force Login Attempt

## Summary

Multiple failed login attempts were detected on a Windows endpoint.

## Detection

Tool:
Wazuh SIEM

Event:
Windows Authentication Failure

Severity:
High

## Investigation

Reviewed:
- Event timestamp
- Username
- Source machine
- Number of failed attempts

## Findings

Repeated failed login attempts indicated possible brute force activity.

## Response

Recommended:
- Account lockout policy
- Monitoring source activity
- Reviewing user accounts

## Status

Closed
