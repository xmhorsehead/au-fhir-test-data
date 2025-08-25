
# Synthetic Data Properties

- **Conformance**: The synthetic data generated aims to conform to the structures and constraints defined in the corresponding HL7 AU FHIR Implementation Guides, as indicated. Some data may be intentionally non-conformant to support negaitve testing scenarios.

- **Anonymity and Realism**: All data is synthetic, containing no personally identifiable information (PII) or protected health information (PHI). It is generated to approximate real-world properties and relationships found in actual healthcare data to support testing and development. Any resemblance to real entities is purely coincidental.
  - Personas included in the dataset (Patients, Practitioners, PractitionerRoles, Organizations, Healthcare Services and Locations)
    - Names are randomly picked or supplied by Service Australia.
    - Addresses are valid addresses based on publicly available address data from Australia Post.
    - Australian phone numbers are from [the reserved set provided by the Australian Communications and Media Authority for use in creative works](https://www.acma.gov.au/phone-numbers-use-tv-shows-films-and-creative-works). 
    - Email addresses use the following domains set aside for development and testing: 'example', 'myownpersonaldomain domain', and 'my-own-personal-domain domain'. 
    - Resources with an IHI, HPI-I, or HPI-O have been provided by Services Australia and are present in the HI Vendor Test Environment. These resources may be in tests within that environment.
    - IHIs, HPI-Os, HPI-Is are provided by Services Australia for test purposes and will pass Luhn check. 
    - Medicare Card Numbers and DVA numbers are provided by Services Australia for test purposes.
    - Australian Health Practitioner Regulation Agency (Ahpra) Registration Numbers are provided by Services Australia for test purposes.
    - ABNs present in the data for fictious organisations are not valid ABNs, i.e. they will not pass validity checks.
  - Other clinical resources included in the dataset 


- **Unbiased**: The dataset is intended to avoid biases in data representation.

- **Variation**: The dataset aims to exhibit sufficient variation to effectively test different aspects of HL7 AU FHIR IGs, helping to validate a range of expected behaviours and constraints.

- **Data Integrity**: Relationships between different entities are maintained as accurately as possible. For example, *PractitionerRoles* are appropriately linked to *Practitioners* and *Organizations*, reflecting real-world associations.

# HL7 Australia License and Legal

## Licensing Overview

This repository [`hl7au / au-fhir-test-data`](https://github.com/hl7au/au-fhir-test-data) and its release packages for the [HL7 AU FHIR Test Data project](https://confluence.hl7.org/spaces/HA/pages/184927329/HL7+Australia+Project+Registry) are licensed under the [Creative Commons Legal Code (Creative Commons Zero v1.0 Universal)](https://github.com/hl7au/au-fhir-test-data/blob/master/docs/LICENSE.md#CreativeCommonsLegalCode).

## HL7 Australia Intellectual Property Policy

HL7 Australia has an overarching intellectual property policy in place. The [HL7 Australia - Intellectual Property Policy](https://hl7.org.au/fhir/hl7a_ip_policy.pdf) document defines the HL7 Australia organisation's position on many aspects related to copyright, licensing, and liabilities. This policy document is maintained with the current official position of HL7 Australia with respect to these considerations.

## Disclaimer and Warning of Use

HL7 Australia provides HL7 Australia content for informational and reference purposes. While HL7 Australia and the broader HL7 community endeavour to ensure the accuracy and reliability of HL7 Australia content, to the extent permitted by law, HL7 Australia:

1. **Makes no warranties, express or implied:**
    (i) that HL7 Australia content will not infringe upon any third-party intellectual property rights, including patents, copyrights, trademarks, or trade secrets; or
    (ii) that HL7 Australia content is suitable, complete, or applicable for any particular purpose or use contemplated by the User.
2. **Shall not be liable** for any direct, indirect, incidental, special, consequential, or punitive damages arising out of or in connection with the use or reliance on HL7 Australia content.

By accessing or using HL7 Australia content, Users agree to indemnify and hold harmless HL7 Australia, its officers, directors, employees, agents, and contributors of HL7 Australia content from any claims, damages, losses, liabilities, costs, or expenses (including legal fees) arising out of or in connection with the User’s use of or reliance on HL7 Australia content.

