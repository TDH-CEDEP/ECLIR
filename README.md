# Electronic Case and Laboratory Interoperability Repository (ECLIR)
Developed for the Tennessee Department of Health (TDH)

## Overview
The Electronic Case and Laboratory Interoperability Repository (ECLIR) is a standards-
based framework developed for the Tennessee Department of Health to modernize
monitoring, parsing, and analysis of electronic laboratory reporting (ELR) and electronic
case reporting (eCR).

ECLIR enhances visibility, data quality, and interoperability by consolidating message
parsing, validation, structured error capture, and analytics within a unified environment.
TDH is sharing this repository to support other public health jurisdictions pursuing similar
modernization efforts.

## What ECLIR Provides

ECLIR enables:
- Automated parsing of HL7 and CDA messages
- Structured ELR validation using TDH, NBS, and NIST
- Error processing and classification for rapid troubleshooting
- Centralized storage of raw and transformed message content
- Dashboards and analytics for message completeness, volume, and error trends
- Designed with modular, scalable architecture suitable for additional message types or programs

These capabilities provide a strong starting point for jurisdictions aiming to improve
ELR/eCR monitoring and data quality.

## How Jurisdictions Can Leverage ECLIR

Public health agencies vary in infrastructure and workflows. ECLIR is designed so
jurisdictions can:
- Reuse core parsing and validation logic
- Adapt the architecture to local Rhapsody or other interface engines
- Tailor database design for local reporting conditions and code sets
- Extend dashboards using Tableau, Power BI, or other visualization tools
- Retrieve unique identifiers and critical data points from the NEDSS Base System (NBS) surveillance system
- Integrate additional data sources over time

**Note:** Adoption will require environment-specific configuration, routing updates, and
jurisdictional validation rules.

## Future Vision
TDH is sharing this work to contribute to broader public health modernization. Long-term,
ECLIR can support:
- Repeatable models for ELR/eCR data quality improvement
- Standardized dashboards and completeness metrics across jurisdictions
- More consistent national informatics practices

Jurisdictions are encouraged to adapt the framework with acknowledgement to TDH.

## About the Developers

ECLIR was collaboratively developed by:
- Tennessee Department of Health (TDH) – Surveillance Systems & Informatics Program
- J Michael Consulting (JMC) – Provided full-lifecycle delivery including
requirements elicitation, solution architecture, technical implementation, data
engineering, analytics, governance, release coordination, and post-deployment
support

For jurisdictions seeking implementation assistance or customization support, J Michael
Consulting (JMC) may be contacted at: innovation@jmichael-consulting.com

## Acknowledgement

Please credit the Tennessee Department of Health when reusing or adapting components
of this solution.
