query params:
rmin, rmax, imin, imax: complex plane boundaries

example: 
?rmin=-0.751&rmax=-0.735&imin=0.118&imax=0.134


todo:

Use compute pipeline to calculate Mandelbrot set:*
https://surma.dev/things/webgpu/

Display raw data in a canvas using canvas2D and drawImage:
  https://stackoverflow.com/questions/12553265/draw-raw-image-into-canvas

Probably easier: Display raw data in a canvas using canvas2D and createImageData/putImageData:*
https://www.w3schools.com/jsref/canvas_createimagedata.asp
  Possible to copy webgpu output directly to imageData.data?
  Otherwise use a naive approach and iterate pixel by pixel. Example: http://jsfiddle.net/gaziya/0m2ysujp/47/

Alternative:
  Make the Mandelbrot calculation per pixel in a fragment shader.

  https://codelabs.developers.google.com/your-first-webgpu-app#0


Separate number of color cycles for each of r,g,b

Set canvas size by query params


