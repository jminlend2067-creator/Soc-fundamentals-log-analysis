# SOC Fundamentals Log Analysis (TryHackMe)
SOC Fundamentals lab from TryHackMe- log analysis and threat detection
## Overview
This project documents a SOC Fundamentals lab completed on TryHackMe. The lab focuses on analyzing logs to detect suspicious activity and understand how Security Operations Centers (SOC) identify potential threats.
## Objectives
- Analyze log data for suspicious behavior
- Identify potential security threats
- Understand SOC investigation workflow
- ## Tools & Skills
- Log analysis
- Basic Linux commands
- Security monitoring concepts
- Threat detection
- ## Investigation Process

### Step 1: Reviewing Logs
I started by examining the provided logs to understand the structure and identify key fields such as timestamps, IP addresses, and usernames.

### Step 2: Identifying Suspicious Activity
I searched for unusual patterns such as repeated failed login attempts.

### Step 3: Analyzing Login Attempts
I found multiple failed login attempts from a single IP address, indicating a possible brute force attack.

### Step 4: Confirming Suspicious Behavior
A successful login occurred after several failed attempts, confirming suspicious activity.
## Key Findings
- Detected multiple failed login attempts
- Identified potential brute force attack
- Observed successful login after repeated failures
- Suspicious IP activity identified
- ## Flag
THM{your_flag_here}
## What I Learned
- How SOC analysts detect attacks using logs
- Importance of monitoring authentication logs
- How brute force attacks appear in real data
