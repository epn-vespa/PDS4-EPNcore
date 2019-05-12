This VESPA/EPNcore LDD version proposes a nested architecture corresponding to VESPA/EPNcore attributes classification in the VESPA/EPNcore documentation, except for the _c1*_, _c2*_, and _c3*_ elements, that are replaced by explicit attribute names.
        
# Features:
* nested VESPA/EPNcore attributes in XML label
* explict _c1*_, _c2*_, and _c3*_ coordinate names
* _s_region_ is decomposed into pieces, making validation possible
* added (__min_, __max_) to _subsolar_longitude_, _subsolar_latitude_, _subobserver_longitude_, _subobserver_latitude_, _ra_, _dec_, _radial_distance_, _altitude_fromshape_
* _bib_reference_ is described (and is validated) either as a _bibref_, a _doi_ or an _url_.
* Detached extension classes: 
  * Particle_Spectroscopy_Extension_Parameters, 
  * Solar_System_Ojects_Extension_Parameters
  * Experimental_Spectroscopy_Extension_Parameters
  * APIS_Extension_Parameters
            
 # Current issues:
* _c1*_, _c2*_, and _c3*_ not defined as the VESPA/EPNcore model

