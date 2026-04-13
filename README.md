# eSim Upgradation – Task 4 (FOSSEE Summer Fellowship 2026)

## Overview
This repository presents the analysis and resolution of installation issues encountered while setting up eSim 2.5 on a modern Ubuntu environment. The work focuses on identifying compatibility problems and improving the installation process for newer systems.

## Environment
- Operating System: Ubuntu 24.04 LTS (Virtual Machine)
- Virtualization Tool: Oracle VM VirtualBox
- Shell: Bash
- Python Version: Python 3.x

## Methodology
The following steps were carried out during this task:

1. Executed the eSim installation script on Ubuntu  
2. Captured installation logs and identified failure points  
3. Analyzed dependency-related and compatibility issues  
4. Investigated root causes using system tools and documentation  
5. Modified installation script and system configuration where required  
6. Re-tested the installation steps to validate fixes  

---

## Issues Identified

### Issue 1: Python Dependency Error
- **Description:** Installation failed due to missing or outdated Python reference  
- **Cause:** The script used deprecated package naming (`python`) not supported in newer Ubuntu versions  

---

### Issue 2: Missing Package Dependency
- **Description:** Required libraries were not found during installation  
- **Cause:** Some dependencies are not pre-installed or have updated names in Ubuntu 24.04  

---

### Issue 3: (Optional – add if you got another error)
- **Description:** [Write your error]  
- **Cause:** [Reason]  

---

## Fix Implemented

### Fix for Python Dependency Issue
The installation script was updated to use the correct Python version supported by modern Ubuntu systems.

**Changes made:**
- Replaced deprecated package reference:
