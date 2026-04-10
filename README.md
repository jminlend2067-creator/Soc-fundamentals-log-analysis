# SOC Fundamentals Log Analysis (TryHackMe)
SOC Fundamentals lab from TryHackMe focused on log analysis and threat detection
---

## Overview
This project documents a SOC Fundamentals lab completed on TryHackMe. The lab focuses on analyzing logs to detect suspicious activity and understanding how Security Operations Centers (SOC) identify and respond to potential threats.

---

## Objectives
- Analyze log data for suspicious behavior
- Identify potential security threats
- Understand SOC investigation workflow

---

## Tools & Skills
- Log analysis (authentication logs, event review)
- Basic Linux command knowledge
- Security monitoring concepts (SOC operations)
- Threat detection and anomaly identification

---

## Investigation Process

### Step 1: Log Review
I analyzed the provided logs to understand their structure, focusing on key fields such as timestamps, usernames, and IP addresses.

### Step 2: Detecting Suspicious Activity
I identified repeated failed login attempts from a single IP address, indicating potential brute-force behavior.

### Step 3: Correlation Analysis
I correlated multiple failed login attempts with a successful login event from the same source.

### Step 4: Confirmation
This pattern confirmed suspicious activity consistent with a brute-force attack.

---

## Key Findings
- Detected multiple failed login attempts from a single source
- Identified behavior consistent with a brute-force attack
- Observed a successful login following repeated failures
- Identified suspicious IP activity associated with authentication attempts

---
## Flag
THM{000_INTRO_TO_SOC}

*Flag obtained through analysis of SOC fundamentals and lab completion tasks.*
---

## What I Learned
- How SOC analysts analyze authentication logs to detect threats
- The importance of identifying patterns such as brute-force attacks
- How correlating events helps confirm suspicious activity
- The role of continuous monitoring in SOC operations
## Screenshots

[![Log Analysis](log-analysis.png)](log-analysis.png)  
*Log review and structure analysis*

[![Failed Logins](failed-logins.png)](failed-logins.png)  
*Repeated failed login attempts from a single IP*

[![Suspicious Activity](suspicious-activity.png)](suspicious-activity.png)  
*Detection of abnormal login behavior*
---

## Professional Growth
This lab allowed me to strengthen my understanding of SOC operations and defensive security. What stood out to me most was how small patterns in logs, such as repeated failed logins, can reveal larger attack behavior like brute-force attempts.
Beginning to adopt an SOC mindset is helping me approach investigations more critically and analytically. This lab helped me better understand how SOC analysts think when identifying and validating suspicious activity. I’m continuing to build my skills in log analysis and threat detection as I work toward becoming a SOC analyst.

 README.md
