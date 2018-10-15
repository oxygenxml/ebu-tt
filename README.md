oXygen XML Editor framework for EBU-TT files 
============================================

This project adds EBU-TT validation and visual editing support in oXygen for 
EBU-TT files as an oXygen framework.

Installation
------------

Follow these steps to install the EBU-TT framework  
 - open oXygen
 - go to *Help*->*Install new Add-Ons...* 
 - paste the following update site 
   `https://github.com/oxygenxml/ebu-tt/raw/master/site.xml` - if you want to install from the master branch
   `https://github.com/oxygenxml/ebu-tt/raw/dev/site.xml` - if you want to install from the dev branch
 - select the "oXygen XML Editor framework for EBU-TT" and follow the wizzard 
 to install the framework 

oXygen WebApp
-------------
The framework just associates a schema and a CSS with the document. 
If the schema and the CSS are specified within the document then the validation
and the visual editing will work even without installing the framework. 
For example, we can see how such a document works in the oXygen WebApp using the
our test server to load one of the sample documents directly from GitHub
https://www.oxygenxml.com/webapp-demo-aws/app/demo-mobile.html?url=https://raw.githubusercontent.com/oxygenxml/ebu-tt/master/sample/ebu-tt-samplefile-colours.xml

License
-------

The project is licensed for use under the 
[Apache License 2.0](https://github.com/oxygenxml/ebu-tt/blob/master/LICENSE).

Copyright © 2015, Syncro Soft SRL 





 


