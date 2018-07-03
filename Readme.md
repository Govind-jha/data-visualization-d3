
Collapsible Tree Data Visualization of Coffee Flavours using D3.js
==========================================================================

The original coffee flavour wheel was created by the Specialty Coffee Association of America in poster form but it appears in various places on the Web. Rogers Gourmet Coffee & Tea Market seems to have the most information about its origin:

    …a flavor wheel created in 1997 by the Specialty Coffee Association of America, the Colombian Coffee Federation, and Jean Lenoir. It's part of the poster called, "The Coffee Tasters' Flavor Wheel" that you can buy on the SCAA website. 

Setup a Simple HTTP Server / Local Web Server
-----------------------------------------------

 - Navigate to the project folder, and start a node http server with this command:
```
 % npm install -g http-server
 % http-server
```
 - Command to start a python HTTP server
```
 % python -m SimpleHTTPServer [port-number]
```

Key Features
--------------------------------------------------------------------------
Expanding and collapsing of nodes is achieved by clicking on the desired node.
Dragging can be performed on any node other than root (flare).
Dropping can be done on any node.
Panning can either be done by dragging an empty part of the SVG around or dragging a node towards an edge.
