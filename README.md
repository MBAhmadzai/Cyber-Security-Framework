<img src="/Levels/twt-logo.png" height="100">

# Cyber Security Framework
A Cyber Security Framework for The Wildlife Trusts

## Introduction
This framework establishes a cyber security standard for The Wildlife Trusts, ensuring compliance with legislative and regulatory requirements. It aligns with [Article 32](https://www.legislation.gov.uk/eur/2016/679/article/32) of the UK GDPR, advocating "appropriate technical and organisational measures" based on risk and implementation costs.

Grounded in the National Cyber Security Centre (NCSC) ['10 Steps to Cyber Security'](https://www.ncsc.gov.uk/collection/10-steps), the framework scales proportionally to each Trust's resources and size. Supporting documentation, templates, and technical resources accompany each step.

The framework undergoes review at least every three years or in response to significant legislative, regulatory, or guidance changes.

A [Maturity Model](/Levels/README.md#introduction) outlines measures necessary to meet this standard, considering information system scope and associated risks. The full framework is accessible at [Contents](/Levels/Contents.md).

## Working with Suppliers
Cyber security controls may be implemented by Trust staff, third-party suppliers, or a combination thereof. Clearly defining responsibilities is essential to mitigate risks and prevent security breaches. Trusts should explicitly document supplier responsibilities in agreements.

The [Shared Responsibility Model](/1-Understand-your-risks/shared-responsibility-model.md) facilitates discussions and decision-making regarding control allocation.

## The Standard
Outlined below are the 10 Steps to Cyber Security, with explicit compliance statements for six fundamental security controls.

1. **Risk Management**
2. **Engagement and Training**
   - Senior Management [visibly supports](/1-Understand-your-risks/Step-02-Engagement-and-Training.md#top-down-support) Trust cyber risk controls and demonstrates good cyber hygiene.
   - Staff receive appropriate training to [enhance awareness](/1-Understand-your-risks/Step-02-Engagement-and-Training.md#security-awareness) of cyber risks and their mitigation roles.
3. **Asset Management**
   - Maintaining updated records of [Data](/1-Understand-your-risks/Step-03-Asset-Management.md#data-assets) and [Technology](/1-Understand-your-risks/Step-03-Asset-Management.md#technology-assets) assets.
4. **Supply Chain Security**
5. **Architecture and Configuration**
   - Trust email domains are [configured](/2-Implement-appropriate-mitigations/Step-05-Architecture-and-Configuration.md#make-it-harder-to-spoof-your-email-domain) to prevent spoofing.
   - Effective endpoint protection is [installed](/2-Implement-appropriate-mitigations/Step-05-Architecture-and-Configuration.md#install-effective-endpoint-protection) on all Trust devices.
6. **Vulnerability Management**
   - Systems are [patched and updated](/2-Implement-appropriate-mitigations/Step-06-Vulnerability-Management.md#update-systems), and publicly accessible systems are regularly tested for [vulnerabilities](/2-Implement-appropriate-mitigations/Step-06-Vulnerability-Management.md#scan-for-vulnerabilities).
7. **Identity and Access Management**
   - Access to personal data is [restricted](/2-Implement-appropriate-mitigations/Step-07-Identity-and-Access-Management.md#decide-who-needs-access-to-what-and-how) to authorized personnel and periodically [reviewed](/2-Implement-appropriate-mitigations/Step-07-Identity-and-Access-Management.md#maintain-your-identities).
   - Trusts implement [multi-factor authentication](/2-Implement-appropriate-mitigations/Step-07-Identity-and-Access-Management.md#implement-multi-factor-authentication-mfa-for-all-remote-access) for all remote access and cloud services.
   - Privileged access is [restricted](/2-Implement-appropriate-mitigations/Step-07-Identity-and-Access-Management.md#separate-admin-accounts-and-protect-them) using individually named accounts.
8. **Data Security**
   - Personal data is [encrypted](/2-Implement-appropriate-mitigations/Step-08-Data-Security.md#protect-data-with-encryption) at rest and in transit.
   - Trusts [backup](/2-Implement-appropriate-mitigations/Step-08-Data-Security.md#backup-your-data) data according to sensitivity and protect backups from attack.
9. **Logging and Monitoring**
10. **Incident Management**

