# PDS4-EPNcore

This project proposes [NASA/PDS4](https://pds.jpl.nasa.gov/datastandards/about/) Local Data Dictionary (LDD) for the [VESPA-EPNcore](https://voparis-wiki.obspm.fr/display/VES/EPN-TAP+v2+parameter+description) keyword dictionary. 


## Design Options
Several design options have been explored and are available as branches:
* [option 1](/epn-vespa/PDS4-EPNcore/tree/option1) implements the VESPA-EPNcore model as presented in the VESPA reference document. 
* [option 2](/epn-vespa/PDS4-EPNcore/tree/option2) implements the VESPA-Epncore model with a nested keyword structure. 
* option 3 is not implemented (and will not be). It initially was planned to implement the VESPA-EPNcore model with several sub-LDDs.
* [option 4](/epn-vespa/PDS4-EPNcore/tree/option4) implements the VESPA-Epncore model with explicit spatial coordinate keywords.
* [option 5](/epn-vespa/PDS4-EPNcore/tree/option5) implements the VESPA-Epncore model with explicit spatial coordinate keywords and adds the option to choose a single value or min/max interval for numerical fields.

