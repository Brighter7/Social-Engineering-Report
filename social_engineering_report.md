# Social Engineering Attacks: Impacts, Techniques, and Mitigations

## Executive Summary

Social engineering attacks are among the most significant cybersecurity threats, exploiting human behavior to gain unauthorized access to sensitive information. Rather than targeting technical vulnerabilities, attackers manipulate individuals through deception techniques such as phishing, pretexting, and baiting. These attacks often result in identity theft, financial losses, reputational damage, and disruption of business operations.

This research examines the different types of social engineering attacks, the techniques cybercriminals use to deceive victims, the reasons organizations and individuals remain vulnerable, and the strategies that can be implemented to mitigate these threats.

**Keywords:** Social Engineering, Phishing, Cybersecurity, Human Factors, Information Security

---

# 1. Introduction

Cybersecurity threats continue to increase as attackers shift their focus from exploiting technical weaknesses to manipulating human behavior. Social engineering attacks deliberately target end users through psychological manipulation, encouraging them to reveal confidential information or perform actions that compromise organizational security.

Despite advances in cybersecurity technologies, attackers continue to succeed because human behavior cannot be completely eliminated from information systems. As a result, employees are often regarded as the weakest link in the information security chain, providing attackers with an easier path into systems that may otherwise be difficult to compromise.

Social engineering remains one of the most prevalent cyber threats worldwide. Several high-profile organizations have experienced significant security incidents caused by human manipulation rather than technical failures.

### MGM Resorts (2023)

In 2023, MGM Resorts suffered a major cyberattack initiated through voice phishing (vishing). Attackers gathered publicly available information about an employee from social media platforms, particularly LinkedIn. They impersonated the employee and contacted the company's IT help desk, convincing support personnel to reset the employee's credentials without adequately verifying the caller's identity.

The attack caused widespread operational disruption and financial losses estimated to exceed **US$100 million**.

### Cisco (2022)

In May 2022, Cisco experienced a cyberattack after an employee became the target of a phishing campaign. The attacker compromised the employee's personal Google account, where browser-synchronized credentials had been stored.

Although Cisco enforced Multi-Factor Authentication (MFA), the attacker launched an **MFA fatigue attack**, repeatedly sending authentication requests until the employee eventually approved one. This allowed unauthorized access to portions of Cisco's internal corporate network. Due to Cisco's security controls and rapid incident response, the operational impact remained limited.

### Electronic Arts (EA)

Electronic Arts (EA), one of the world's largest video game publishers, also experienced a significant social engineering attack. The attackers purchased a stolen authentication cookie from an online marketplace, allowing them to access EA's internal collaboration platform while appearing to be legitimate employees.

Approximately **780 GB** of proprietary data was stolen, including:

- FIFA 21 source code
- Frostbite game engine source code
- Software Development Kits (SDKs)
- Internal development tools

Although customer accounts were not compromised, EA suffered substantial intellectual property losses.

---

# 2. Social Engineering Attack Lifecycle

Social engineering attacks typically follow a structured process designed to manipulate victims into performing actions that compromise security.

## 2.1 Reconnaissance

During this phase, attackers gather information about individuals or organizations to build convincing attack scenarios.

Common information sources include:

- LinkedIn profiles
- Social media platforms
- Company websites
- Public records
- News articles
- Data breaches

The objective is to collect sufficient background information to increase the credibility of the attack.

---

## 2.2 Relationship Establishment

After gathering information, attackers initiate contact with the intended victim.

Common methods include:

- Phone calls (vishing)
- Emails
- Social media messages
- Fake IT support requests
- Password verification requests

Attackers impersonate trusted individuals such as:

- Help desk technicians
- Managers
- Executives
- Vendors
- Financial institutions

The success of this phase depends largely on the victim's trust.

---

## 2.3 Exploitation

Once trust has been established, attackers persuade victims to perform actions that compromise security.

Examples include:

- Revealing usernames and passwords
- Clicking malicious links
- Downloading malware
- Approving MFA requests
- Opening malicious attachments
- Transferring money

Victims often believe they are assisting a legitimate request.

---

## 2.4 Execution

Following successful exploitation, attackers execute their objectives.

These objectives may include:

- Identity theft
- Financial fraud
- Data theft
- Corporate espionage
- Ransomware deployment
- Unauthorized access to sensitive systems

---

# 3. Types of Social Engineering Attacks

Various techniques are employed by cybercriminals to manipulate victims into revealing confidential information or granting unauthorized access.

## 3.1 Phishing

Phishing is the most common social engineering attack. Attackers impersonate trusted organizations or individuals to trick victims into disclosing sensitive information.

The objectives may include:

- Stealing login credentials
- Compromising business accounts
- Installing malware
- Bypassing security controls

Attackers commonly use:

- Fake emails
- Fraudulent websites
- Malicious hyperlinks
- Fake advertisements

### Common Types of Phishing

- Email Phishing
- Spear Phishing
- Business Email Compromise (BEC)
- Whaling
- Vishing (Voice Phishing)
- Smishing (SMS Phishing)

---

## 3.2 Pretexting

Pretexting involves creating a believable scenario to convince victims to disclose confidential information.

Attackers often impersonate:

- IT support personnel
- Human Resources staff
- Bank representatives
- Government officials
- Executives

The attacker uses information gathered during reconnaissance to establish credibility and build trust before requesting sensitive information.

---

## 3.3 Baiting

Baiting involves enticing victims with attractive offers or incentives to encourage unsafe actions.

Examples include:

- Free software downloads
- Promotional offers
- Free USB drives
- Prize giveaways
- Fake software updates

The objective is to compromise the confidentiality, integrity, or availability of information systems.

---

# 4. Preventing Social Engineering Attacks

Social engineering remains one of the most difficult cybersecurity threats to defend against because it targets human behavior. Effective defense requires a combination of employee awareness, organizational policies, and technical security controls.

## 4.1 Cybersecurity Awareness Training

Organizations should conduct regular cybersecurity awareness training to educate employees about social engineering techniques and safe online practices.

Training programs should include:

- Phishing simulations
- Password security
- Safe browsing practices
- Reporting suspicious emails
- Social media awareness

---

## 4.2 Multi-Factor Authentication (MFA)

Multi-Factor Authentication adds an additional layer of security by requiring users to verify their identity using multiple authentication methods.

Benefits include:

- Reduced risk of compromised passwords
- Stronger account protection
- Improved access security

---

## 4.3 Identity Verification

Employees should verify the identity of anyone requesting:

- Password resets
- Sensitive information
- Financial transactions
- Administrative privileges

Proper verification procedures help prevent impersonation attacks.

---

## 4.4 Email Security

Email remains the primary delivery method for social engineering attacks.

Organizations should implement:

- Email filtering
- Anti-phishing solutions
- Spam protection
- Attachment scanning
- URL filtering

These controls help detect and block malicious communications before they reach users.

---

## 4.5 Regular System Updates

Keeping operating systems, applications, and firmware up to date helps eliminate vulnerabilities that attackers may exploit.

Organizations should:

- Apply security patches promptly
- Regularly update software
- Replace unsupported systems
- Conduct vulnerability assessments

---

# Conclusion

Social engineering attacks exploit human psychology rather than technical vulnerabilities, making them one of the most effective forms of cyberattack. Their consequences range from financial losses and identity theft to large-scale data breaches and operational disruption.

High-profile incidents involving MGM Resorts, Cisco, and Electronic Arts demonstrate that even organizations with mature cybersecurity programs remain vulnerable to attacks that manipulate human behavior.

Organizations can significantly reduce their risk by implementing comprehensive security awareness training, enforcing Multi-Factor Authentication, verifying identities before granting access, deploying robust email security solutions, and maintaining up-to-date systems through regular patch management.

Ultimately, combining human awareness with strong technical controls provides the most effective defense against social engineering attacks.
