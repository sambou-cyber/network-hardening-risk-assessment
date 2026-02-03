# Security Risk Assessment, Network Hardening.

## Background
A social media organization experienced a major data breach that exposed customer personal information, including names and addresses. An internal review identified multiple security weaknesses that contributed to the breach.

This assessment evaluates the identified vulnerabilities and recommends network hardening controls to strengthen the organization’s security posture and prevent future incidents.


## Identified Vulnerabilities

The following vulnerabilities were identified during the assessment:

1. Employees share passwords, increasing the risk of unauthorized access.
2. The database administrative account uses a default password.
3. Firewall rules are not configured to properly filter inbound and outbound traffic.
4. Multifactor authentication (MFA) is not implemented.

---

## Risk Analysis

These vulnerabilities significantly increase the likelihood of credential compromise, unauthorized system access, and data exposure. Without remediation, the organization remains at high risk for repeat breaches and further compromise of sensitive information.

---

## Recommended Network Hardening Controls

### 1. Enforce Strong Authentication and Multifactor Authentication (MFA)

**Description:**  
Require unique passwords for all users and enforce MFA for administrative and privileged accounts.

**Effectiveness:**  
MFA reduces the risk of account compromise by requiring additional verification beyond a password, even if credentials are stolen or guessed.

**Implementation Frequency:**  
Continuously enforced

---

### 2. Remove Default Credentials

**Description:**  
Replace default passwords on databases and administrative systems with strong, unique credentials.

**Effectiveness:**  
Default credentials are commonly targeted by attackers and represent a critical security risk if left unchanged.

**Implementation Frequency:**  
One-time remediation with periodic audits

---

### 3. Configure Firewall Traffic Filtering

**Description:**  
Implement firewall rules that restrict unnecessary inbound and outbound traffic, allowing only required ports and services.

**Effectiveness:**  
Proper firewall configuration reduces the attack surface and limits unauthorized access to internal systems.

**Implementation Frequency:**  
Reviewed quarterly or after network changes

---

## Conclusion

Implementing these network hardening controls strengthens authentication mechanisms, reduces exposure to external threats, and significantly lowers the likelihood of future data breaches. Regular reviews and enforcement of security policies are essential to maintaining a secure network environment.
