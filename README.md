# WebGL Plugins

WebGL (Web Graphics Library) is a JavaScript API for rendering high-performance interactive 3D and 2D graphics within any compatible web browser without the use of plug-ins. WebGL does so by introducing an API that closely conforms to OpenGL ES 2.0 that can be used in HTML5 <canvas> elements. This conformance makes it possible for the API to take advantage of hardware graphics acceleration provided by the user's device.
  
Javascript has evolved into a language capable of handling realtime 3D graphics, via WebGL, and computationally intensive tasks such as physics simulations. These types of applications demand high performance vector and matrix math, which is something that Javascript doesn't provide by default. glMatrix to the rescue!

glMatrix is designed to perform vector and matrix operations stupidly fast! By hand-tuning each function for maximum performance and encouraging efficient usage patterns through API conventions, glMatrix will help you get the most out of your browsers Javascript engine.
##glMatrix
Regarding the current performance in modern web browsers, calling glMatrix.setMatrixArrayType(Array) to use normal arrays instead of Float32Arrays can greatly increase the performance.
