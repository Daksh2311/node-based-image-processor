# Node-based-image-processor
This is a node-based image editing application built using Qt C++. Users can load images, apply transformations like blur, crop, rotate, and save the output — all through an interactive node-graph interface.
## Features
Drag-and-drop node creation<br>
Image loading, viewing, and saving<br>
Graph-based UI to build image processing pipelines<br>
## Support for nodes like:
Read<br>
View<br>
Write<br>
Blur<br>
Crop<br>
Rotate<br>
Gamma<br>
## Architecture Overview
MainWindow: Hosts the canvas and menu.<br>
GraphicsView: Custom scene for rendering nodes.<br>
Node: Base class for all processing nodes.<br>
DerivedNodes: Specific implementations like ReadNode, ViewNode, etc.<br>
## Getting Started
### Prerequisites
Qt Creator (>= Qt 5.x or 6.x)
### Build Instructions
Clone the repo or download the source<br>
Open Image-Editor.pro in Qt Creator<br>
Build and run<br>
### Usage
Right-click on canvas → Add node<br>
Connect nodes (click-and-drag from socket)<br>
Configure properties (e.g., blur radius)<br>
View or save final image<br>
