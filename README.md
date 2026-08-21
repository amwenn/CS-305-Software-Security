# CS 305 Software Security Portfolio

## Developer

Ambren Cavazos

## Artifact

For this course, I selected my completed Artemis Financial Practices for Secure Software Report as my portfolio artifact. This artifact shows my ability to apply secure coding practices, use checksum verification, configure secure communication, and test a software application for security concerns.

## Reflection

Artemis Financial was the client for this project. The company provides financial planning services and wanted to improve the security of its web application. The main issue the company wanted addressed was protecting sensitive client and financial information. Artemis Financial needed secure communication and a way to verify that data had not been changed during transfer.

One thing I did well was identifying areas where the application needed stronger security controls. I looked at secure communication, checksum verification, certificate use, dependency testing, and manual code review. It is important to code securely because insecure code can expose private information, damage customer trust, and create financial or legal problems for a company. Software security adds value to a company because it protects data, reduces risk, and helps maintain the company’s reputation.

The most challenging part of the vulnerability assessment was understanding how all the security tools and settings worked together. For example, using Java Keytool, configuring HTTPS, and running OWASP Dependency-Check required careful steps. This was also helpful because it showed me that security is not only about writing code. It also includes configuration, testing, and reviewing third-party dependencies.

I increased layers of security by adding SHA-256 checksum verification and configuring the application to use HTTPS on port 8443. The checksum helped support data integrity, while HTTPS helped secure communication between the browser and the application. In the future, I would use tools such as OWASP Dependency-Check, manual code review, secure coding standards, and vulnerability assessment reports to decide which mitigation techniques are needed.

I made sure the code and software application were functional and secure by running the refactored application, testing the /hash endpoint, and confirming that the browser displayed the checksum output. I also reviewed the code for syntax errors, logic errors, and security concerns. After refactoring the code, I ran OWASP Dependency-Check to see whether the application had known dependency vulnerabilities or if my changes introduced new issues.

The resources, tools, and coding practices I used included Java, Spring Boot, Java Keytool, SHA-256, HTTPS configuration, OWASP Dependency-Check, and manual testing. These tools and practices will be useful in future assignments because they help identify vulnerabilities, protect data, and improve the quality of software.

For future employers, I could show this artifact as an example of my ability to apply secure software development practices. It demonstrates that I can review security requirements, use cryptographic hashing, configure HTTPS, run dependency testing, and explain how security improves an application. This project shows my growth in understanding how secure coding protects users and organizations.
