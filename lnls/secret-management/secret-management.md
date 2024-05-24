# Secret Management

# :question: What is a secret?
A secret is **any piece of sensitive information** that, if compromised by a malicious entity, can be used to cause serious damage to an organization or product's security, functionality, reputation, or financial well-being.

Some common examples:
- **Authentication credentials** - passwords, API keys
- **Encryption/signing keys**
- **Non-public cryptographic materials** - private keys, root/intermediate certificates
- **Confidential data** - customer information, trade secrets, personnel files
- **Authorization policies** - access control lists, system permissions

# :question: Why should I care about properly managing my secrets?
Securely handling and managing secrets is crucial for several reasons:
- **Prevent data breaches** - If a malicious entity gains access to sensitive information, such as passwords or signing keys, they can compromise the security of our systems and data.
- **Protect user trust** - If confidential data is leaked or compromised, users will lose trust in our ability to keep their information safe. This can, and often does, result in irreparable reputational damage and loss of business.
- **Regulatory compliance** - Many industries, countries, and desired certifications have strict legal requirements around how sensitive data is handled and stored. Failure to comply with these regulations results in consequences ranging from serious financial fines to criminal charges.
- **Maintain system integrity** - When sensitive information falls into the wrong hands, it can lead to a costly and time-consuming crisis. Instead of focusing on innovating products or delivering top-notch support to our customers, we'll be stuck in damage control mode - scrambling to contain the breach, investigate the incident, and patch up vulnerabilities. 
- **Reduce risk of accidental leaking** - Even the most well-intentioned employees may accidentally leak sensitive information. Proper handling and storage of secrets can help reduce the possibility of this happening and limit the blast radius when/if it does.

# :question: What are some common mistakes related to managing secrets?
- Sharing over insecure mediums (slack, email)
- Storing unencrypted secrets in plaintext
- Storing secrets in easily-accessible locations (post-it notes on your desk, CSV files)
- Reusing secrets across services/applications
- Using insecure, short, and non-randomly generated strings as secret values

# :hammer: Available Tooling

## Personal/Individual Account Secret Management
- [1Password](https://1password.com/personal)
- [LastPass](https://www.lastpass.com/products/personal)

## Application/Service Account Secret Management
- [HashiCorp Vault](https://www.hashicorp.com/products/vault)
- [Amazon Secrets Manager](https://aws.amazon.com/secrets-manager/)
- [1Password](https://1password.com/developers)

# :open_book: Further Reading
- [General Data Protection Regulation - GDPR](https://gdpr-info.eu)
  - [Consequences of GDPR non-compliance](https://www.gdprhandbook.eu/consequenses-gdpr)
- [California Consumer Privacy Act - CCPA](https://www.oag.ca.gov/privacy/ccpa)
  - [A quick reference guide for CCPA compliance](https://www2.deloitte.com/us/en/pages/advisory/articles/ccpa-compliance-readiness.html)
- [SOC2](https://www.imperva.com/learn/data-security/soc-2-compliance/)
- [Federal Risk and Authorization Management Program - FedRAMP](https://www.fedramp.gov)
- [Personal Information Protection and Electronic Documents Act - PIPEDA](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/)
  - [All about PIPEDA, Canada's version of HIPPA](https://www.accountablehq.com/post/all-about-pipeda-canadas-version-of-hipaa)
- [Health Insurance Portability and Accountability Act - HIPAA](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)
