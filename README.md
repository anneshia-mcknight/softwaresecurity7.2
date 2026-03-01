# softwaresecurity7.2
This one started from 7-2 Portfolio Prep. 

This repository contains my selected portfolio artifact for the course. Artemis Financial – Practices for Secure Software Report. The file demonstrates my ability to apply secure coding techniques, strengthen an existing application through encryption, certificate generation, testing, and refactoring.

**Reflection**
**1) Client Summary**
Artemis Financial is a financial consulting company that creates customized plans. They needed to modernize their software and ensure secure communication within their public-facing web application. My task was to identify vulnerabilities, add a file-verification step using a checksum, and implement secure communication mechanisms.

**2) Strengths in Identifying Vulnerabilities**
I located weaknesses in the original application and applied modern security techniques — such as implementing SHA-256 hashing and enforcing HTTPS. Secure coding protects client data, prevents breaches, and increases trust as the critical factors for any organization handling sensitive financial information.

**3) Challenges**
The most challenging aspect was ensuring all refactored components complied with testing protocols, especially when integrating the dependency-check tool. However, this process helped reinforce how security layers interact inside a real application.

**4) Increasing Layers of Security**
I improved security by adding SHA-256, generating a self-signed certificate, enabling HTTPS, and reviewing dependencies for vulnerabilities. In the future, I would continue using tools such as OWASP Dependency-Check, static analysis scanners, and secure coding guidelines to decide which mitigation techniques are most appropriate.

**5) Ensuring**
After refactoring, I tested the application manually and verified that the server ran correctly over HTTPS. I also re-ran the dependency-check scan to ensure no new vulnerabilities were introduced. Functional testing confirmed that the updated code executed without errors.

**6) Resources**
Resources included Java Keytool, SHA-256, Maven with OWASP Dependency-Check, the Spring Boot application structure, and secure coding practices.

**7) What I Can Show**
This demonstrates my ability to secure an existing codebase, implement encryption, perform vulnerability assessments, run security testing tools, write technical documentation, and deliver production-ready enhancements. It is a strong example of my practical software-security skills.
