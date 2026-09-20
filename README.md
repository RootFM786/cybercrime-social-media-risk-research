# Cybercrime and Social Media Risk Research

## Overview

This repository presents a university cybersecurity research project examining the relationship between **social media use and cybercrime risk among UK small businesses**.

The project combined a literature review with a small primary-data study of **12 UK small businesses** in the retail and service sectors. The aim was to understand how heavily small businesses rely on social media, how aware they are of cybercrime, and whether that awareness translates into practical defensive action.

> This was a research project, not a technical lab. Its portfolio value is in **risk analysis, evidence interpretation, security awareness and translating findings into practical recommendations**.

## Research Question

**Has the rise in social media contributed to increased cybercrime risk for small businesses?**

The original report focused particularly on social engineering, phishing, ransomware, data breaches and other risks that can be amplified by online behaviour and information exposure.

## Method

The study used a mixed-method survey of 12 purposely selected UK small businesses.

Participants had to:

- operate in the retail or service sector
- be based in the UK
- use at least two major social-media platforms

The survey combined quantitative questions with open-ended responses about perceived cyber risk, business impact and examples of suspicious activity.

## Key Finding

The strongest finding was a clear **awareness–action gap**:

- business owners generally showed awareness of common cyber threats
- social media was heavily relied upon for marketing and customer engagement
- participants believed cybercrime could seriously damage their businesses
- but only **2 of the 12 businesses** reported taking proactive steps to reduce cyber risk

This is the most security-relevant finding in the project.

## Why This Matters for Security Analysts

A security analyst is not only investigating alerts. Good security work also depends on understanding **why risky behaviour happens and where technical controls may fail because of human behaviour**.

| Research Finding | Analyst / Security Relevance |
|---|---|
| Heavy social-media reliance | Larger public attack surface and more opportunities for social engineering |
| Awareness without action | Knowing about threats does not guarantee controls are implemented |
| Social-media information exposure | Can support phishing, impersonation and credential attacks |
| Small-business resource constraints | Helps explain weaker security controls and slower remediation |
| High perceived business impact | Supports risk-based prioritisation and business-impact analysis |

## Security Risk Themes

### Social Engineering

The original research identified social engineering as one of the clearest links between social media and cybercrime.

Examples included users disclosing information that could help attackers build convincing phishing or impersonation attempts.

### Phishing

Phishing was discussed as a major cybercrime route because attackers can use publicly available information to make messages appear more credible.

### Business Continuity

Participants said losing access to important systems or social-media accounts could significantly disrupt operations.

This highlighted that cybersecurity risk is not only about data theft; **availability and recovery also matter**.

## Practical Security Recommendations

The original project recommended that small businesses:

1. take proactive cybersecurity steps such as awareness training, outsourcing specialist support or implementing security policies
2. put recovery measures in place before an incident occurs
3. continually update their awareness of evolving cyber threats

See [risk-findings.md](docs/risk-findings.md) for the findings in a more security-focused format.

## Analyst-Focused Interpretation

The project can be reframed as a basic **human-risk assessment**:

```text
Public information exposure
        ↓
Social engineering opportunity
        ↓
Phishing / impersonation attempt
        ↓
User decision
        ↓
Credential compromise or malicious access
        ↓
Operational / financial impact
```

See [analyst-skills-mapping.md](docs/analyst-skills-mapping.md).

## Skills Demonstrated

- cyber-risk research
- social-engineering awareness
- phishing-risk analysis
- mixed-method data collection
- evidence interpretation
- security awareness analysis
- risk communication
- translating findings into recommendations
- recognising methodological limitations

## Limitations

The study had a small, deliberately selected sample of 12 businesses, so the findings should not be treated as representative of all UK small businesses.

No participant reported being a known victim of cybercrime, which also limits conclusions about direct causation between social-media use and actual compromise.

## Retrospective

With my current security-operations perspective, I would improve the project by:

- separating exposure, vulnerability and confirmed compromise more clearly
- measuring which security controls each business actually had in place
- distinguishing phishing awareness from phishing resilience
- including MFA, password management, account recovery and email-security controls
- recording past incidents and near misses
- mapping social-engineering scenarios to observable security events
- using a larger and more representative sample

The strongest lesson from this project is that **security awareness only has value when it results in practical controls and safer behaviour**.

## Repository Structure

```text
.
├── README.md
└── docs/
    ├── risk-findings.md
    ├── analyst-skills-mapping.md
    └── methodology-and-limitations.md
```