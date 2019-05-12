This EPN VESPA LDD version propose a nested architecture corresponding to EPN VESPA attributes classification in the EPN VESPA documentation

## Features:
* nested EPN VESPA attributes in XML label
* _s_region_ is decomposed into pieces, making validation possible
* added (_*_min_, _*_max_) suffixes to _subsolar_longitude_, _subsolar_latitude_, _subobserver_longitude_, _subobserver_latitude_, _ra_, _dec_, _radial_distance_, _altitude_fromshape_
* _bib_reference_ is describes either as a _bibref_, a _doi_ or an _url_.

## Current issues:
* _c1*_, _c2*_, and _c3*_ names are defined several times (with different _local_identifier_). This confuses the validation engine and false errors on units are reported.
