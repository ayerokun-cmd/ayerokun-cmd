# Hi, I'm Anu Yerokun 👋

### Third-party risk (TPRM) assessor moving into cloud security · CISA · AWS Solutions Architect – Associate

> I assess risk for a living. Now I'm building the controls too.

For 6+ years I've worked in **fintech and financial services**, assessing vendors, systems and cloud environments, and proving to regulators, auditors and boards that they're secure. Now I design and build those controls myself, in AWS.

[![Portfolio](https://img.shields.io/badge/Portfolio-ayerokun--cmd.github.io-0A66C2?style=for-the-badge&logo=githubpages&logoColor=white)](https://ayerokun-cmd.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anu--yerokun-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anu-yerokun)
[![Email](https://img.shields.io/badge/Email-anuyerokun%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anuyerokun@gmail.com)

---

## 🧭 How I work

**Assess first, then design.** I find the risk, map it to a control, and show the evidence. From TPRM I bring a focus on vendor risk, solid evidence and clear remediation, and I apply it to cloud architecture.

## 🚀 Featured projects

### [AWS Secure VPC Baseline](https://github.com/ayerokun-cmd/aws-secure-vpc-baseline)
A secure, multi-AZ, three-tier AWS network written in **CloudFormation**. It has an isolated data tier, chained security groups, KMS-encrypted flow logs, and SSM access with no bastion host. It ships with an **organization-wide guardrail policy (SCP)** and a **control mapping to NIST CSF 2.0, ISO 27001:2022 and PCI DSS v4.0**. Every commit is checked automatically with cfn-lint and the Checkov security scanner.

### [Cloud Security Posture Checker](https://github.com/ayerokun-cmd/cloud-posture-checker)
A read-only **Python + boto3** CLI that audits an AWS account against **25 controls from the CIS AWS Foundations Benchmark v3.0.0**. It writes a Markdown/JSON risk report with a posture score, severity ratings, remediation steps and the API evidence behind every finding, like an assessor's report for the cloud. Checks it couldn't evaluate are reported as coverage gaps, never as passes, and a `--fail-on` exit code lets it gate CI/CD pipelines. See the [sample report](https://github.com/ayerokun-cmd/cloud-posture-checker/blob/main/docs/sample-report.md).

### [Sentinel](https://github.com/ayerokun-cmd/sentinel): endpoint detection
A cross-platform scanner for malware and weak security settings on Windows, macOS, Linux, Android and iOS. It shows my endpoint detection work, which complements my cloud focus.

## 🎯 Next up

- A secure AWS reference architecture in **Terraform**, with a threat model and architecture decision notes
- **AWS Certified Security – Specialty**, my next certification after SAA

## 🏅 Certifications

| Certification | Issuer | Year |
|---|---|---|
| **AWS Certified Solutions Architect – Associate** | Amazon Web Services | 2026 |
| **Certified Information Systems Auditor (CISA)** | ISACA | 2025 |
| **Microsoft Certified: SQL Server & BI (70-448)** | Microsoft | — |
| **CRISC** | ISACA | *In progress* |

## 🛠️ What I do

- **Architect secure AWS environments.** I design multi-AZ and multi-region networks with VPC segmentation, private subnets, Transit Gateway and least-privilege IAM, following all six pillars of the Well-Architected Framework.
- **Build for resilience.** I use Auto Scaling, Elastic Load Balancing, Route 53 failover, RDS Multi-AZ, and backup and disaster-recovery plans with defined RTO and RPO targets.
- **Make security the default.** I enforce KMS envelope encryption, permission boundaries, SCPs, GuardDuty, Security Hub, and CloudFormation guardrails.
- **Optimize cost.** I right-size resources, use Savings Plans, set S3 lifecycle policies, and build serverless, event-driven designs (Lambda, API Gateway, DynamoDB).
- **Bring audit-grade governance.** I work across NIST CSF/RMF, ISO 27001, SOC 2, PCI-DSS, SOX 404, GDPR and HIPAA.

## 🧰 Tech stack

**Cloud & compute**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![ECS / Fargate](https://img.shields.io/badge/ECS%20%2F%20Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF4F8B?style=flat-square&logo=amazonapigateway&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step%20Functions-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)

**Data & storage**
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![RDS / Aurora](https://img.shields.io/badge/RDS%20%2F%20Aurora-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Security & identity**
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazoniam&logoColor=white)
![KMS](https://img.shields.io/badge/KMS-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![GuardDuty](https://img.shields.io/badge/GuardDuty-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![Security Hub](https://img.shields.io/badge/Security%20Hub-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=flat-square&logo=okta&logoColor=white)
![SailPoint](https://img.shields.io/badge/SailPoint-0033A1?style=flat-square)

**Infrastructure as code & operations**
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=flat-square&logo=servicenow&logoColor=white)

**Governance, risk & compliance**
`TPRM` `NIST CSF / RMF` `ISO 27001/2` `SOC 2` `PCI-DSS` `SOX 404` `ITGC` `GDPR` `HIPAA` `COBIT` `COSO` `AuditBoard` `GRC Archer`

## 💼 Experience

| Role | Company | Dates |
|---|---|---|
| Security & Technology Risk Analyst | **Moniepoint** | Jun 2026 – Present |
| GRC & Cloud Risk Analyst (Contract) | **Brinks Bank** | Jun 2025 – May 2026 |
| IT Auditor / Cloud Security & GRC Analyst | **Citigroup** | Aug 2023 – Jun 2025 |
| IT Auditor / SOX Compliance Analyst | **The Home Depot** | Oct 2022 – Aug 2023 |
| IT Auditor / Risk Analyst | **Target** | Dec 2019 – Oct 2022 |
| Senior Business Analyst | **Target / T-Mobile** | Sep 2017 – Dec 2019 |

### 📈 Selected impact

- **−40%** mean incident-response time at Citigroup, through structured escalation paths
- **+30%** regulatory adherence from the GDPR and SOX GRC frameworks I built
- **−25%** compliance violations after cloud, IAM and network control assessments
- **−30%** audit findings at The Home Depot, working with Big 4 external auditors
- **85%** of high-risk vulnerabilities remediated on schedule at Target
- **100%** SOX compliance across financial systems

## 🎓 Education

- **B.S., Psychology**, Arizona State University
- **A.S., Computer Science**, Pima Community College

---

📍 Based in Mexico · Open to cloud security, solutions architecture and cloud GRC roles
