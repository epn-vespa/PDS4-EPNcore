This EPN VESPA LDD version propose a flat architecture corresponding to EPN VESPA attributes.
        
## Features:
* all EPN VESPA attributes at same level in XML label

## Current issues:
* _c1*_, _c2*_, and _c3*_ can't have _@unit_. This will be problematic for mapping with other LDDs, and make validation more complex.
* _s_region_ is provided is an STC string. No validation process available. 
* _bib_reference_ should be split in various subtypes for validation
* _particle_spectral_*_min_ and _particle_spectral_*_max_ units can't be described (no _@unit_)
* _access_format_ missing ASCII_Mime_Type value_data_type
* likely attributes missing (_*_min_, _*_max_) suffixes: _subsolar_longitude_, _subsolar_latitude_, _subobserver_longitude_, _subobserver_latitude_, _ra_, _dec_, _radial_distance_, _altitude_fromshape_, _mass_, _sideral_rotation_period_, _mean_radius_, _equatorial_radius_, _polar_radius_
