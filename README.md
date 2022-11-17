# SRI Testing Documentation

User, Test File Curator, Administrator and Developer Documentation for the SRI Testing TRAPI Test Harness.

## User Documentation

The NCATS Biomedical Data Translator [TRAPI Resource Validator Web Dashboard](https://sri-testing.apps.renci.org/) presents results of validation of various knowledge graph semantic unit tests run with TRAPI queries autogenerated from test edge data curated by Knowledge Provider (KP) owners and test configurations curated by Autonomous Relay Agent (ARA) owners.  Validation of the TRAPI request and response contents relating to queries against these KP and ARA components are validated against specified [TRAPI](https://github.com/NCATSTranslator/ReasonerAPI) and [Biolink Model](https://biolink.github.io/biolink-model/) versions. 

### Table of Contents

- [Operation of the Web Dashboard](./web_dashboard_operations.md)
- [Knowledge Graph Semantic Tests](./kg_unit_test_definitions.md)
- [Validation Message Codes](https://translator-reasoner-validator.readthedocs.io/en/latest/#validation_code_definitions.md)

## Test File Curator Documentation

The SRI Testing harness uses KP test edge data and ARA test configurations provided by KP and ARA component owners, respectively, who we designate here as "Test File Curators". The current guidelines for test / configuration file composition - relating to the current generation of "One Hop" unit tests - is provided on the main SRI Testing harness web site [here](https://github.com/TranslatorSRI/SRI_testing/blob/main/tests/onehop/README.md).

## Administrator Documentation

For the moment, the main SRI Testing harness web site [here](https://github.com/TranslatorSRI/SRI_testing/blob/main/README.md) provides basic documentation on the design and deployment details of the SRI Testing harness, for administrators relating to production deployment and maintenance of the web dashboard and back end validation engine, in 'production' environments.

## Developer Documentation

For the moment, the main SRI Testing harness web site [here](https://github.com/TranslatorSRI/SRI_testing/blob/main/README.md) provides basic documentation on the design and deployment details of the SRI Testing harness, for developers interested in further development of the application.
