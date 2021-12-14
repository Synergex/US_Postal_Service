# US_Postal_Service<br />
**Created Date:** 11/14/2005<br />
**Last Updated:** 10/19/2010<br />
**Description:** Programs which provide examples of using the "City/State Lookup", "Rate Calculator" and "Track/Confirm" web services from the United States Postal Service. The examples use the XML API and HTTP API to communicate with these web services. (Update for Synergy 9.5 compatibility)<br />
**Platforms:** Windows; Unix; OpenVMS<br />
**Products:** HTTP API; XML API<br />
**Minimum Version:** 8.3<br />
**Author:** Steve Ives
<hr>

**Additional Information:** Description of routine
----------------------

This routine is intended to show how to use use the USPS web services that
allow address validation, zip code lookup and US domestic postal rate
calculations.

You will need a USPS User ID. This can be obtained (for free) by registering
at http://www.usps.com/webtools You can also get full documentation on all
USPS web services at this website.

Prototype command: DBLPROTO USPSaddressValidation.dbl USPSrateCalculator.dbl
Compiler command: DBL uspsTest.DBL USPSaddressValidation.dbl USPSrateCalculator.dbl
Link command DBLINK uspsTest.DBO DBLDIR:synxml.elb
Files: uspsTest.DBL, USPSaddressValidation.dbl & USPSrateCalculator.dbl
