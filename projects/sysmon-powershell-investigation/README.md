# Sysmon PowerShell Process Investigation

## Overview

This investigation focused on using Microsoft Sysmon and Windows Event Viewer to investigate PowerShell process creation and understand Windows process relationships.

The objective was to develop practical SOC analyst skills in endpoint telemetry analysis, process investigation, and identifying parent-child process relationships.

## Environment

- Operating System: Windows 10 Home
- Sysmon: Microsoft Sysinternals Sysmon
- Log Source: Microsoft-Windows-Sysmon/Operational
- Investigation Tool: Windows Event Viewer
- Analysis Tool: Windows PowerShell
- Sysmon Event ID: 1 — Process Create

## Objectives

- Install and configure Sysmon on a Windows endpoint
- Understand how Sysmon generates endpoint telemetry
- Investigate Windows process creation events
- Identify parent and child processes
- Analyse PowerShell execution
- Determine whether observed activity appears legitimate or suspicious
- Practise documenting findings from a SOC analyst perspective

## Investigation

### 1. Sysmon Event ID 1

Sysmon Event ID 1 records process creation events.

The event provides information including:

- Process image
- Process ID
- Command line
- User
- Integrity level
- File hash
- Parent process
- Parent command line

This information can be used by security analysts to investigate how a process was launched and identify potentially suspicious process relationships.

### 2. PowerShell Process Identified

A Sysmon Event ID 1 event was identified for:

```text
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
