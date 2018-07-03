
Collapsible Tree Data Visualization of Coffee Flavour Wheel using D3.js
==========================================================================

Overview
--------------------------------------------------------------------------
A Data Visualization model of Coffee Flavour wheel using trees in D3.js. It has an editor version in which it adds a context menu for renaming, deleting and creating nodes. Right-click on a node to get the context menu for rename, delete and create. The tree auto-calculates its sizes both horizontally and vertically so it can adapt between many nodes being present in the view.

Data Background
--------------------------------------------------------------------------
Coffee Taster’s Flavor Wheel is one of the most iconic resources in the coffee industry. It's a product of dozens of professional sensory panelists, scientists, coffee buyers, and roasting companies collaborating via World Coffee Research (WCR) and the Specialty Coffee Association of America (SCAA). This is the largest and most collaborative piece of research on coffee flavor ever completed, inspiring a new set of vocabulary for industry professionals.

Setup a Simple HTTP Server / Local Web Server
--------------------------------------------------------------------------

 - Navigate to the project folder, and start a node http server with this command:
```
 % npm install -g http-server
 % http-server
```
 - Command to start a python HTTP server
```
 % python -m SimpleHTTPServer [port-number]
```

Now open index.html in any modern web browser.

Key Features
--------------------------------------------------------------------------
 - Scroll Up/Down to Zoom In/Out the canvas.
 - Expanding and collapsing of nodes is achieved by clicking on the desired node.
 - Dragging can be performed on any node other than root (flare).
 - Dropping can be done on any node.
 - Panning can either be done by dragging a node towards an edge.
 - Create, Update and Delete nodes.
