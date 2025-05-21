# MITRE ATT&CK: Step-by-Step Guide to Attacker Tactics

This guide breaks down the 14 core stages of an attacker’s operation as defined in the MITRE ATT&CK framework. Each stage is essential to understand how attackers plan, execute, and complete cyberattacks — and how defenders can detect and stop them.

---

## 1. Reconnaissance
**What it is:** The attacker gathers information about the target.  
**Goal:** Learn who, what, and where to attack.

**Examples:**
- Scanning your website
- Searching LinkedIn for employees
- Finding open ports

---

## 2. Resource Development
**What it is:** The attacker builds or purchases tools and infrastructure.  
**Goal:** Prepare for the attack.

**Examples:**
- Creating phishing websites
- Writing malware
- Buying stolen credentials or fake domains

---

## 3. Initial Access
**What it is:** The attacker gains access to your system or network.  
**Goal:** First step inside.

**Examples:**
- Sending a phishing email with a malicious link
- Exploiting a vulnerable server
- Logging in with stolen credentials

---

## 4. Execution
**What it is:** The attacker runs malicious code on the system.  
**Goal:** Launch the payload.

**Examples:**
- Running a backdoor or malware
- Opening a malicious attachment
- Executing PowerShell scripts

---

## 5. Persistence
**What it is:** The attacker ensures continued access to the system.  
**Goal:** Remain inside after reboot or logout.

**Examples:**
- Creating hidden user accounts
- Installing a backdoor
- Modifying startup settings

---

## 6. Privilege Escalation
**What it is:** The attacker obtains higher-level permissions.  
**Goal:** Gain full control.

**Examples:**
- Exploiting a vulnerability to become admin
- Stealing a more privileged user’s credentials

---

## 7. Defense Evasion
**What it is:** The attacker avoids detection.  
**Goal:** Stay hidden.

**Examples:**
- Disabling antivirus software
- Obfuscating malicious code
- Clearing logs

---

## 8. Credential Access
**What it is:** The attacker tries to steal usernames, passwords, or tokens.  
**Goal:** Gain legitimate access.

**Examples:**
- Keylogging
- Dumping password hashes
- Internal phishing

---

## 9. Discovery
**What it is:** The attacker explores the system and network.  
**Goal:** Understand the environment.

**Examples:**
- Mapping internal systems
- Finding file shares
- Identifying active users

---

## 10. Lateral Movement
**What it is:** The attacker moves between systems inside the network.  
**Goal:** Reach valuable targets.

**Examples:**
- Remote Desktop Protocol (RDP) access
- Using stolen credentials to log into other machines

---

## 11. Collection
**What it is:** The attacker gathers target data.  
**Goal:** Prepare for data theft or misuse.

**Examples:**
- Copying sensitive documents
- Logging keystrokes
- Capturing screenshots

---

## 12. Command and Control (C2)
**What it is:** The attacker communicates with compromised systems remotely.  
**Goal:** Maintain control and issue commands.

**Examples:**
- Malware contacting an external server
- Attacker sending instructions to download or encrypt files

---

## 13. Exfiltration
**What it is:** The attacker steals and transmits the data out of the network.  
**Goal:** Get the data out.

**Examples:**
- Uploading data to cloud storage
- Sending data via encrypted email

---

## 14. Impact
**What it is:** The attacker causes harm to systems or data.  
**Goal:** Disrupt, destroy, or demand ransom.

**Examples:**
- Deploying ransomware
- Deleting critical files
- Defacing a website

---


