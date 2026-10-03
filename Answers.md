# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
Pillow 9.4.0. The vulnerability allows arbitrary code execution through the environment parameter of PIL.ImageMath.eval.

2. Which CVE is linked to this vulnerability?
CVE-2023-50447


3. What remediation steps do you suggest?
Upgrade Pillow from version 9.4.0 to version 10.2.0 or later, which contains the fix for this vulnerability.

### Vulnerability 2:
1. Which vulnerability are you addressing?
PyJWT 2.4.0. The vulnerability involves improper verification of a cryptographic signature.

2. Which CVE is linked to this vulnerability?
CVE-2026-102268

3. What remediation steps do you suggest? 
Upgrade PyJWT from version 2.4.0 to version 2.14.0 or later, which contains the fix for this vulnerability.
