#d3.js Sunburst Partition

- forked from http://bl.ocks.org/kerryrodden/477c1bfb081b783f80ad

"I combined Mike Bostock's [Zoomable Sunburst](http://bl.ocks.org/mbostock/4348373) and [Sunburst Partition](http://bl.ocks.org/mbostock/4063423) examples, so that I could have both zooming and updating the underlying data (between count and size, in this case). A simple combination of the examples does not work; you have to edit the arcTween function used for updating the data, so that when it redraws the partition layout, it takes account of the current zoom level by adjusting the domain of the x scale.

Click on any arc to zoom in, and click on the center circle to zoom out. Use the Size/Count radio buttons to update the data."

#How to use

- fork the project
- npm install http-server -g
- http-server
- http://localhost:8888/ 

- and that's it, you can see the result
