QUOTER – POSTA DEL ESTE
=========================

This project is a simple online quotation tool used to check
availability and pricing for rental periods at Posta del Este.

The tool is published as a web page and can be accessed through
a public link. It does not require login, installation, or any
special software to use.

------------------------------------------------------------

WHAT THIS IS
------------

• A static web page that shows rental availability and prices  
• Generated automatically from an Excel file  
• Used internally to prepare and share quotations  

There is no server, no database, and no automatic data source.
Everything is generated beforehand.

------------------------------------------------------------

HOW IT IS UPDATED
-----------------

All prices and availability are maintained in Excel.

When something changes:

1) The Excel file is updated  
2) A macro generates a new web file called:

   index.html

3) That file replaces the previous one in this repository  
4) The website updates automatically within 1–2 minutes  

Nothing else needs to be configured.

------------------------------------------------------------

LIVE VERSION
------------

The current live version is available at:

https://sergitoq.github.io/Cotizador/

This link always points to the latest published version.

------------------------------------------------------------

IMPORTANT NOTES
---------------

• The file index.html is GENERATED automatically  
• It should not be edited manually  
• The filename must remain exactly:

  index.html

• Character encoding is UTF-8  
• The application runs entirely in the browser  

------------------------------------------------------------

INTENDED USE
------------

This tool is intended for internal or controlled use to:

• Quickly check availability  
• Generate consistent quotations  
• Share information with clients  

It is not designed as a public product or general-purpose software.

------------------------------------------------------------

LICENSE / USAGE
---------------

Private use only.
Not intended for redistribution or commercial resale.
