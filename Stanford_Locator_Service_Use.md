# Using Stanford's locator.stanford.edu Geocoding Service

Stanford Geospatial Center maintains an ArcGIS Server-based geocoding service for research and teaching use. This service is meant to be used for bulk geocoding of thousands to millions of placenames and/or addresses in North America.

### To access the Address Locator services:

* In ArcCatalog, or the Catalog Panel in ArcMap, expand the GIS Servers item
* Double-click the Add ArcGIS Server item
* Leave the default "Use GIS Services" option, click Next>
* For the 'Server URL' use: https://locator.stanford.edu/arcgis
* For 'User Name' use your **SUNetID** (prefixed with the 'WIN\' domain) as **WIN\SUNetID**
* Enter the password associated with your SUNetID and check the option to Save Username/Password
* Click Finish

You should then be able to use the various Address Locator Services for bulk geocoding in ArcGIS.

## What's Currently Available on locator.stanford.edu

The address locators inside the geocode folder include a Composite (capable of street addresses and postal codes) service for North America and separate services for U.S. Street Addresses and Postal Codes.

The address locators in the Rio folder include Address Locators built by [The Spatial History Project](http://web.stanford.edu/group/spatialhistory/cgi-bin/site/index.php) at Stanford's [Center for Spatial and Textual Analysis (CESTA)](https://cesta.stanford.edu/). For more information about these geocoding services, see the Spatial History Project's [Rio de Janeiro Historical Address Locator](http://web.stanford.edu/group/spatialhistory/cgi-bin/site/viz.php?id=123&project_id=999) page.

### Are You an R User?

Stanford Library's Claudia Engel maintains a repo with scripts for using the Stanford Geocoding Service in R. Find them here: [https://github.com/cengel/ArcGIS_geocoding](https://github.com/cengel/ArcGIS_geocoding)

### For More Information

For more information about the Geocoding Process in ArcGIS, see [Esri's What is Geocoding? Guide](http://desktop.arcgis.com/en/desktop/latest/guide-books/geocoding/what-is-geocoding.htm).
