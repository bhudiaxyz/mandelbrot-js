Mandelbrot.js
=============

TODOs:
  * Ability to minimize settings console
  * Let dragging work outside window boundaries
  * Enable Julia rendering
  * Let dragging work over description and info box areas
  * Detect slow renderings and display ETA for them
  * Fix the auto-iterations function; consider creating an expanded polynomial
  for it.
  * Add right-click to zoom out (instead of shift-click)
  * Add panning
  * Only render new parts when panning
  (maintain startx and stopx in an array[height of canvas],
   update this array when panning has finished, and then restart
   rendering. Rendering updates this array when a scanline has
   been copied to the canvas).
  * When resizing window, scale up the canvas bitmap before rerendering.
