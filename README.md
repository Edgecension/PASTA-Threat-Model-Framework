# PASTA Threat Model Framework

## Objective
To perform a threat model of a mobile app for a ficticious footwear business using the PASTA framework. Will go through each of the seven stages of the framework to identify security requirements.

## Stage 1: Defining Business and Security Objectives
- Users can create member profiles internally or by connecting external accounts.
- The app must process financial transactions.
- The app should be in compliance with PCI-DSS.

## Stage 2: Defining the Technical Scope
List of technologies used by the application:
- Application programming interface (API)
- Public key infrastructure (PKI)
- SHA-256
- SQL

APIs facilitate the exchange of data between customers, partners and employees, so they should be prioritized. They handle a lot of sensitive data while they connect various users and systems together. However, details such as which APIs are being used should be considered before prioritizing one technology over another. So, they can be more prone to security vulnerabilities because there’s a larger attack surface.

## Stage 3: Decompose Application
<img width="914" alt="Screenshot 2025-05-20 at 11 16 37 AM" src="https://github.com/user-attachments/assets/1ff20ec5-44c4-41b4-a7dd-b5db69fcb09e" />

## Stage 4: Threat Analysis
- Injection
- Session hijacking

## Stage 5: Vulnerability Analysis
- Lack of prepared statements
- Broken API token

## Stage 6: Attack Modeling
<img width="711" alt="Screenshot 2025-05-20 at 11 18 42 AM" src="https://github.com/user-attachments/assets/e3e93654-567e-4b36-80d1-3e054ab98fc7" />

## Stage 7: Risk Analysis and Impact
- SHA-256, incident response procedures, password policy, principle of least privilege
