# universal-data-management
Universal data management library (example application use) for Node.JS

To be ported as a package for NPM if proven sucessful 

Experimental universal data readout (and in most cases manipulation)

Designed as a (mostly) universal API access to PLCs in mind
and to be used for CMS => ECM applications

Datatypes from API calls are to be transpiled on the fly to their respective protocol counterparts

Initial version will (mostly) support the following PLC protocols:
 - Siemens S7comm (R/W)
 - Beckhoff ADS (R/W)
 - Omron FINS (R/W)

Possible future support for:
 - OPC-UA (R)
 - REST API (R/W)
 - TCP API (custom) (R/W)

