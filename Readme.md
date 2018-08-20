
Interactive Visualization of Coffee Flavors using D3.js
==========================================================================

- [Key Features](https://github.com/Govind-jha/data-visualization-d3/blob/master/Readme.md#key-features)
- [Prerequisites](https://github.com/Govind-jha/data-visualization-d3/blob/master/Readme.md#prerequisites)
- [Getting  Started](https://github.com/Govind-jha/data-visualization-d3/blob/master/Readme.md#getting-started) 
- [Background](https://github.com/Govind-jha/data-visualization-d3/blob/master/Readme.md#background)

Key Features
--------------------------------------------------------------------------
 - _Scroll Up/Down to Zoom In/Out the canvas._
 - _Expanding and collapsing of nodes is achieved by clicking on the desired node._
 - _Dragging can be performed on any node other than root (coffee flavour Tree)._
 - _Dropping can be done on any node._
 - _Panning can be done by dragging a node towards an edge._
 - _Create, Update and Delete nodes._


Prerequisites
--------------------------------------------------------------------------

* Any Web Browser (supports javascript)
* HTTP Server

Getting Started 
--------------------------------------------------------------------------
You will need to publish the files on any http server, and then open the webpage in a web browser.

#### Using python
- Navigate to the project folder, and start a simple http server with this [command](https://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/):

```  
 python -m SimpleHTTPServer [port-number]
```

#### Using node

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

Background
--------------------------------------------------------------------------
Coffee Taster’s Flavor Wheel is one of the most iconic resources in the coffee industry. It's a product of dozens of professional sensory panelists, scientists, coffee buyers, and roasting companies collaborating via World Coffee Research (WCR) and the Specialty Coffee Association of America (SCAA). This is the largest and most collaborative piece of research on coffee flavor ever completed, inspiring a new set of vocabulary for industry professionals.
&nbsp;
#### Motive ####

- To create a Data Visualization model of a Hierarchical Data Structure using trees in D3.js. 
- Provide an editor interface to the users for renaming, deleting and creating nodes. 
- Allow CRUD (Create, Read, Update, Delete) operations in the UI.
) 
