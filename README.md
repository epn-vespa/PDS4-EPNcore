# PDS4-EPNcore

This project proposes [NASA/PDS4](https://pds.jpl.nasa.gov/datastandards/about/) Local Data Dictionary (LDD) for the [VESPA-EPNcore](https://voparis-wiki.obspm.fr/display/VES/EPN-TAP+v2+parameter+description) keyword dictionary. 

## Purpose
The [Virtual European Solar and Planetary Access](https://europlanet-vespa.eu) (VESPA) project has defined a set of metadata keywords dedicated to Solar System science data discovery called EPNcore (standing for _Europlanet Core Metadata_). It is currently used with the [Table Access Protocol](http://www.ivoa.net/documents/TAP/) (TAP) as the main data discovery protocol of the VESPA project, namely EPN-TAP. TAP is defined and maintained by the [International Virtual Observatory Alliance](http://ivoa.net) (IVOA). EPNcore includes metadata allowing to describe data products in terms of content (physical quantities, processing level, target, instrument...), access (format, URL...) or coverage (temporal, spectral, spatial...). The full list of keywords is currently maintained by the VESPA team. 

The _Planetary Data System (version 4) Information Model_ (NASA/PDS4 IM) is an archive standard developed by NASA and endorsed by the _International Planetary Data Alliance_ (IPDA). It is built upon industry standard technology and provides an implementation of the _Open Archive Information System_ (OAIS). Its governance model implements several layers of stewardship for dedicated and specialized metadata, which can be provided in a _Local Data Dictionary_ (LDD). 

The VESPA team proposes a LDD for the EPNcore keyword dictionary, including eventually the mappting with existing NASA/PDS4 keywords, so that the NASA/PDS4 search interface can be queried using the EPNcore model. 

## Design Options
The VESPA-EPNcore has been designed as a flat model, so that it can easily be represented into a simple table.  

Several design options have been explored and are available as branches in this repository:
* [option 1](/epn-vespa/PDS4-EPNcore/tree/option1) implements the VESPA-EPNcore model as presented in the VESPA reference document. 
* [option 2](/epn-vespa/PDS4-EPNcore/tree/option2) implements the VESPA-Epncore model with a nested keyword structure. 
* option 3 is not implemented (and will not be). It initially was planned to implement the VESPA-EPNcore model with several sub-LDDs.
* [option 4](/epn-vespa/PDS4-EPNcore/tree/option4) implements the VESPA-Epncore model with explicit spatial coordinate keywords.
* [option 5](/epn-vespa/PDS4-EPNcore/tree/option5) implements the VESPA-Epncore model with explicit spatial coordinate keywords and adds the option to choose a single value or min/max interval for numerical fields.

