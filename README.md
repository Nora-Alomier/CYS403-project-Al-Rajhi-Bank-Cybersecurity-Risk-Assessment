# Al Rajhi Bank — Cybersecurity Risk Assessment

A security analysis of Al Rajhi Bank's digital banking environment, done for the CYS403 course at Prince Sultan University. The report looks at how the bank protects its online and mobile banking services today, where the real risk sits, and what a stronger security posture would look like going forward.

## Why Al Rajhi Bank

Al Rajhi Bank is one of the largest banking institutions in Saudi Arabia, serving over 19 million customers through more than 200 digital services. That scale is exactly what makes it worth studying: a bank this size sits under constant pressure from phishing campaigns, fake banking apps, credential theft, and fraud, while also being bound by SAMA regulation and PDPL data protection requirements. It's a realistic environment for practicing risk assessment rather than a toy example.

## What the report covers

- **Current security environment** — the technical controls (encryption, RBAC, 24/7 SOC monitoring) and organizational measures (governance, employee training, fraud education) the bank already has in place, based on its published policies and fraud-awareness materials.
- **Past and recent incidents** — a look at documented cyber-attacks and fraud attempts targeting the bank and its customers, including how the threat pattern has shifted from early internet-banking malware to today's mobile-first phishing and fake-app schemes.
- **Major security issues** — six recurring problem areas: phishing and social engineering, fraudulent banking apps, account takeover, data privacy exposure, transaction manipulation, and the growing attack surface from digital banking expansion.
- **Risk register and risk matrix** — ten identified risks (`R1`–`R10`), each scored by likelihood and impact, mapped to the information system component it threatens, and paired with existing controls and a recommended treatment.
- **Authentication and data confidentiality evaluation** — a closer look at MFA/OTP verification, role-based access control, and encryption/tokenization, including where each one falls short in practice.
- **Policy and customer guideline analysis** — how the bank's privacy policy, fraud awareness materials, and consumer protection principles hold up against what customers actually need to stay safe.
- **Proposed enhanced security approach** — ten concrete recommendations, from phishing-resistant MFA and adaptive risk-based access control to stronger third-party API security and incident response testing, each tied back to how it improves confidentiality, integrity, or availability.

## Repository structure

```
cys403-alrajhi-bank-security-assessment/
├── README.md
├── diagrams/
│   └── risk-matrix.jpeg         # Likelihood × impact scoring matrix used in the risk register
└── docs/
    └── CYS403_Alrajhi_Bank_Security_Report.pdf   # Full report
```

## Course context

Prepared for **CYS403** at Prince Sultan University, College of Computer and Information Sciences.
Supervised by **Dr. Samah Abdullah Y Almutlaq**.

## Team

Dana Alassaf, Wadha Alarifi, Noura Alalshaikh, Nora Alomier
