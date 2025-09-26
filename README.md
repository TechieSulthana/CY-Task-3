# Task 3: Basic Vulnerability Scan on Localhost

## Objective
Perform a basic vulnerability scan on your PC using a free vulnerability scanner (Nessus Essentials) and identify common security issues.

## Tools Used
- **Nessus Essentials** (Free Vulnerability Scanner)
- **Localhost / PC IP** as scan target

## Steps Performed
1. Installed Nessus Essentials and activated with the provided activation code.
2. Created a **Basic Network Scan** targeting the local machine.
3. Launched the scan and waited for completion (~30–60 minutes).
4. Reviewed the scan results, including severity of vulnerabilities and informational findings.
5. Documented the critical findings, observations, and recommended mitigations.
6. Captured screenshots of the scan summary and detailed vulnerability page for reporting.

## Findings
- **Medium Severity:** 1 vulnerability (SMB Signing Not Required)  
- **Informational:** 18 findings (system configurations and exposed services)

## Observations
- The system has one notable medium-risk vulnerability related to SMB Signing.  
- Informational findings highlight services and configurations that could be leveraged by attackers.  
- No critical or high-severity vulnerabilities were detected.

## Recommended Fixes
- Enable SMB Signing to prevent potential man-in-the-middle attacks.  
- Apply all pending Windows security updates.  
- Disable unnecessary services (e.g., SMBv1, NetBIOS).  
- Configure firewall rules to limit exposed services to trusted networks.  

## Conclusion
The system is **moderately secure** but requires minor mitigations to reduce exposure. Implementing the suggested fixes will enhance the security posture and minimize potential attack vectors.

## Deliverables
- `Task3_Vulnerability_Scan_Report.pdf` (contains detailed findings and screenshots)
- Screenshots of scan summary and vulnerability details
