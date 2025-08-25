HL7 AU FHIR Test Data contains sample FHIR instances for testing purposes, and to support developers. This repository includes synthetic (realistic but not real) data that conforms to HL7 AU FHIR Implementation Guides (IGs). The synthetic data covers a broader and expanded content scope over that in the FHIR instance examples included in published HL7 AU FHIR IGs.

>[!WARNING]
>All data in this data set is synthetic and for test purpose only. They contain no personal or protected health information. Any resemblance to real entities is purely coincidental.

## How to navigate this repository
Synthetic FHIR test data (JSON) files are available in the [au-fhir-test-data-set](/au-fhir-test-data-set) directory: 
  - Includes sample FHIR instances for testing purposes, covering AU Core 1.1.0-preview, eRequesting 0.3.0-preview, and AU Base 5.1.0-preview. 
  - Patient, RelatedPerson, Practitioner, PractitionerRole, Organization, HealthcareService, and Location instances are generated from Services Australia (SA) provided data then enriched with additional elements for AU Core Must Support elements and some extra AU Base elements.
  - A limited set of non-SA personas created to test where an IHI is not present in the data.
  - Includes test data for verifying missing data and suppressed data test cases (for details see [MissingAndSuppressedData_TestData.md](docs/MissingAndSuppressedData_TestData.md)).

The following patients in the dataset have AU Core clinical resources associated:
- baratz-toni
- irvine-ronny-lawrence
- italia-sofia
- howe-deangelo
- hayes-arianne
- baby-banks-john
- banks-mia-leanne
  
The following patients in the dataset have AU eRequesting clinical resources associated:
- belger-remedios
- roberts-fred

## Links

### Release Strategy and Versioning
[The release strategy]() establishes a framework for versioning, release management, and iterative development for HL7 AU FHIR Test Data.

### Test Data Coverage of HL7 AU FHIR Implementation Guides
The test dataset is developed on a best-effort basis, aiming to provide broad coverage of HL7 AU IG profiles and extensions. The extent of coverage evolves iteratively, shaped by the maturity of the IGs, shifting priorities of HL7 AU projects, available resources, and community contributions. For example, in the case of the AU Core IG, the dataset includes coverage of Must Support elements within AU Core profiles and extensions. The current coverage is documented in [AUCoreTestDataCoverage.md](docs/AUCoreTestDataCoverage.md).
