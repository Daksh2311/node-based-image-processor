# node-based-image-processor
This is a node-based image editing application built using Qt C++. Users can load images, apply transformations like blur, crop, rotate, and save the output — all through an interactive node-graph interface.
Features
Drag-and-drop node creation


Image loading, viewing, and saving


Graph-based UI to build image processing pipelines


Support for nodes like:


Read


View


Write


Blur


Crop


Rotate


Gamma


Architecture Overview
MainWindow: Hosts the canvas and menu.


GraphicsView: Custom scene for rendering nodes.


Node: Base class for all processing nodes.


DerivedNodes: Specific implementations like ReadNode, ViewNode, etc.


Getting Started
Prerequisites
Qt Creator (>= Qt 5.x or 6.x)


Build Instructions
Clone the repo or download the source


Open Image-Editor.pro in Qt Creator


Build and run


Usage
Right-click on canvas → Add node


Connect nodes (click-and-drag from socket)


Configure properties (e.g., blur radius)


View or save final image
