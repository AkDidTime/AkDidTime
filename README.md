# Hi, I'm AkDidTime 👋

### Aspiring SOC Analyst | Cybersecurity | IT Support

I'm an aspiring **SOC Analyst** building a career in cybersecurity, with a background in IT Support and a **T Level in Digital Production, Design and Development**, awarded by Pearson.

As part of my T Level, I completed **two years of industry placement in IT Support**, gaining practical experience in a professional IT environment. My experience included endpoint management, patch remediation, remote administration, troubleshooting, PowerShell, technical documentation, and user support.

I'm now building on this foundation through hands-on cybersecurity labs, security investigations, and technical projects focused on **Security Operations, detection, log analysis, incident response, and threat hunting**.

---

## 🎓 Education

### T Level — Digital Production, Design and Development

**Pearson**

* Completed a 2-year T Level programme
* Completed 2 years of industry placement as part of the qualification
* Developed practical technical, problem-solving, and professional skills
* Gained real-world experience working within an IT environment

---

## 💼 Industry Experience

### IT Support — 2-Year Industry Placement

During my industry placement, I gained hands-on experience supporting users, managing endpoints, troubleshooting technical issues, and working within a professional IT environment.

A key area of my experience was **endpoint patch management and remediation**.

#### Patch Management & Remediation

* Used **ConnectWise Manage** to monitor endpoints and identify machines with failed patch deployments
* Used **ConnectWise Automate** to locate and remotely access affected machines
* Investigated failed patch deployments and troubleshot endpoint issues
* Used **PowerShell** to manually download and apply Microsoft updates using their KB IDs
* Recorded patches that repeatedly failed across multiple machines
* Documented recurring patch failures, including patch names and KB IDs
* Investigated patterns in recurring endpoint issues to support troubleshooting and remediation

This experience developed my practical skills in:

**Endpoint Management · Troubleshooting · Remote Administration · PowerShell · Patch Management · Technical Documentation · Problem Solving**

These skills have provided a strong technical foundation that I'm now applying to cybersecurity and Security Operations.

---

## 🔐 Cybersecurity Focus

I'm currently developing skills in the following areas:

* Security Operations (SOC)
* SIEM & Log Analysis
* Security Monitoring
* Threat Detection
* Incident Response
* Threat Hunting
* Windows Security
* Linux Security
* Network Security
* Security Automation
* MITRE ATT&CK
* Digital Forensics Fundamentals

My goal is to develop the ability to investigate security events from initial detection through to analysis, documentation, and recommended remediation.

---

## 🛠️ Tools & Technologies

### Professional / Industry Experience

* **ConnectWise Manage**
* **ConnectWise Automate**
* **PowerShell**
* **Windows**
* Endpoint Management
* Remote Administration

### Cybersecurity Labs & Development

* **Wazuh**
* **Splunk**
* **Sysmon**
* **Wireshark**
* **Linux**
* **Git & GitHub**
* Python

I'm continuing to expand this toolkit through hands-on labs and security investigations.

---

## 📂 Cybersecurity Projects

I'm building hands-on projects to demonstrate practical SOC and cybersecurity skills.

### 🚧 SOC Home Lab

Building a small security monitoring environment to practise:

* Endpoint monitoring
* Log collection
* SIEM configuration
* Security alert analysis
* Detection engineering
* Incident investigation

### 🚧 Windows Event Log Investigation

Investigating Windows security events to understand:

* Authentication activity
* Failed and successful logins
* Suspicious processes
* Account activity
* Indicators of potential compromise


### 🔎 Sysmon Process Investigation

Performed a hands-on investigation using **Sysmon** and Windows Event Viewer to analyse process creation telemetry.

The investigation focused on:

* Analysing Sysmon Event ID 1 (Process Create)
* Examining process command lines
* Identifying parent and child processes
* Reconstructing a process tree
* Investigating PowerShell and `conhost.exe` activity
* Reviewing process hashes and integrity levels
* Determining whether observed activity appeared suspicious or legitimate
* Documenting investigation findings

**Key finding:**

```
explorer.exe
    |
    └── powershell.exe
            |
            └── conhost.exe
```

The observed PowerShell execution was consistent with legitimate interactive activity. The process tree showed `explorer.exe` launching PowerShell, which in turn spawned `conhost.exe`. No suspicious command line, unusual parent process, or other indicators of compromise were identified during this investigation. The investigation demonstrated how process relationships and endpoint telemetry can be used to establish context around security events.

**Tools used:**

* Sysmon
* Windows Event Viewer
* PowerShell
* Windows Event Logs


### 🚧 Brute Force Detection

Building a detection and investigation workflow for repeated authentication failures.

The project will focus on:

* Identifying suspicious login patterns
* Analysing Windows authentication logs
* Investigating source IP addresses
* Establishing attack timelines
* Mapping activity to **MITRE ATT&CK**
* Documenting investigation findings

### 🚧 Phishing Investigation

Developing an investigation workflow for analysing suspicious emails and identifying potential indicators of compromise.

Areas of investigation will include:

* Email headers
* URLs and domains
* Attachments
* Indicators of compromise
* User impact
* Recommended containment and remediation

### 🚧 Threat Hunting Lab

Developing structured threat-hunting exercises using endpoint and network telemetry.

The focus will be on:

* Developing hypotheses
* Searching security logs
* Identifying suspicious behaviour
* Investigating indicators
* Mapping findings to MITRE ATT&CK
* Documenting conclusions

---

## 🧪 My Approach to Security Investigations

For my cybersecurity projects, I'm developing a consistent investigation methodology:

```text
Alert
  ↓
Collect Evidence
  ↓
Analyse Logs & Activity
  ↓
Identify Indicators
  ↓
Determine Scope & Impact
  ↓
Map to MITRE ATT&CK
  ↓
Document Findings
  ↓
Recommend Remediation
```

The aim is not simply to complete labs, but to develop the analytical and documentation skills expected of a SOC Analyst.

---

## 📈 Current Learning

I'm actively developing my knowledge of:

* SIEM platforms
* Windows event logging
* Security monitoring
* Detection engineering
* Incident response
* Threat hunting
* Network traffic analysis
* Endpoint telemetry
* MITRE ATT&CK
* PowerShell for security
* Python for security automation
* Linux security

---

## 🎯 Career Goal

My goal is to transition from **IT Support into a SOC Analyst / Cybersecurity role**.

I want to combine my existing experience in endpoint management, troubleshooting, PowerShell, and technical support with hands-on cybersecurity skills in security monitoring, threat detection, investigation, and incident response.

This GitHub profile documents that journey through practical labs, investigations, technical projects, and continuous learning.

---

## 📌 Portfolio

This repository is a record of my development toward a career in Security Operations.

As I progress, I will continue adding:

* 🔎 Security investigations
* 🖥️ SOC lab environments
* 🚨 Detection use cases
* 📊 SIEM queries
* 🕵️ Threat-hunting exercises
* 🧪 Incident-response scenarios
* 📝 Investigation reports
* 🛡️ MITRE ATT&CK mappings
* ⚙️ Security automation projects

**I'm building this portfolio to demonstrate not only what I have learned, but how I apply that knowledge to real-world security problems.**
