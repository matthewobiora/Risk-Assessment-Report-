# Risk Assessment on Potential APTs and TTPs Targeting Tower Federal Credit Union

## Project Overview

This project involves a comprehensive risk assessment aimed at identifying potential Advanced Persistent Threats (APTs) and their associated Tactics, Techniques, and Procedures (TTPs) that could target Tower Federal Credit Union (TFCU). The assessment includes a detailed analysis of specific techniques and sub-techniques used by these threat actors, as well as recommendations for mitigating these risks. Furthermore, it evaluates TFCU's current capabilities to handle and mitigate these threats.

## Objectives

1. **Identify Potential APTs:** Research and identify advanced threat groups that pose a risk to TFCU.
2. **Utilizing MITRE ATT&CK Navigator** After we had our 6 groups, we put those APT groups into the MITRE ATT&CK Navigator which shows a dashboard of all the TTPs that these APT groups use. TTPs that are in a shade of red came up more than the TTPs that are in a shade of green. Therefore, red TTPs are those that should be of more concerns

3. **Analyze TTPs:** Evaluate the Tactics, Techniques, and Procedures used by these APTs, with a focus on those most relevant to our organization.
4. **Mitigation Strategies:** Develop and recommend mitigation strategies for each identified technique and sub-technique.
5. **Capability Assessment:** Assess TFCU's current security capabilities and their effectiveness in mitigating identified threats.
## Methodology

### 1. Identification of APTs
Using the MITRE ATT&CK framework, I identified various APT groups that have historically targeted financial institutions. The focus was on APTs with a known interest in targeting financial data and systems.

### 2. Analysis of TTPs
Each identified APT was analyzed to document the specific Tactics, Techniques, and Procedures they employ. This included:

- **Tactics:** The general objectives or purposes of the APTs (e.g., Initial Access, Execution, Persistence).
- **Techniques:** The general methods used to achieve these objectives (e.g., Phishing, Exploiting Public-Facing Applications).
- **Sub-techniques:** More granular actions or methods (e.g., Spear Phishing Link, SQL Injection).

### 3. Mitigation Strategies
For each identified technique and sub-technique, I developed a set of recommended mitigation strategies. These strategies are tailored to the specific methods used by the APTs and include:

- **Preventive Controls:** Measures to prevent the APTs from successfully executing their techniques (e.g., email filtering, patch management).
- **Detective Controls:** Measures to detect the presence of APT activities within the network (e.g., network monitoring, anomaly detection).
- **Responsive Controls:** Measures to respond to and recover from APT activities (e.g., incident response plans, disaster recovery).

### 4. Capability Assessment
I evaluated TFCU's current security posture and capabilities in mitigating the identified threats. This included an assessment of existing technologies, processes, and personnel. The evaluation focused on:

- **Technology:** Effectiveness of current security tools and technologies (e.g., SIEM, EDR, firewalls).
- **Processes:** Adequacy of current security policies, procedures, and incident response plans.
- **Personnel:** Skills and readiness of the security team to handle APT-related incidents.

## Findings

### Identified APT Groups
- **APT28 (Fancy Bear)**
- **APT29 (Cozy Bear)**
- **FIN7**
- **Lazarus Group**
- **Carbanak Group**

### Key Techniques and Sub-techniques
1. **Phishing**
   - **Spear Phishing Link (T1566.001)**
   - **Spear Phishing Attachment (T1566.002)**
2. **Exploitation of Public-Facing Applications (T1190)**
3. **Credential Dumping (T1003)**
   - **LSASS Memory (T1003.001)**
4. **Command and Control (T1071)**
   - **Web Protocols (T1071.001)**
5. **Data Exfiltration (T1041)**

### Mitigation Strategies
- **Phishing Mitigations:**
  - Implement advanced email filtering solutions.
  - Conduct regular phishing awareness training for employees.
- **Exploitation Mitigations:**
  - Regularly patch and update all public-facing applications.
  - Conduct regular vulnerability assessments and penetration testing.
- **Credential Dumping Mitigations:**
  - Employ credential guard solutions.
  - Enforce least privilege access policies.
- **Command and Control Mitigations:**
  - Monitor and analyze network traffic for anomalies.
  - Use DNS filtering to block malicious command and control domains.
- **Data Exfiltration Mitigations:**
  - Implement data loss prevention (DLP) solutions.
  - Monitor outbound network traffic for unusual patterns.

### Capability Assessment
- **Strengths:**
  - Robust SIEM system for real-time threat detection.
  - Comprehensive incident response plan with regular drills.
  - Skilled and trained security personnel.
- **Areas for Improvement:**
  - Need for enhanced email security solutions.
  - Regular updates and patching of legacy systems.
  - Increased focus on user education and awareness.

## Conclusion

The risk assessment has provided valuable insights into the potential APT threats facing TFCU and the techniques they may use. By implementing the recommended mitigation strategies and addressing the identified areas for improvement, TFCU can significantly enhance its security posture and resilience against advanced threats.


