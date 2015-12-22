paleytiles
==========

A toy for playing with animated tiles in SVG, inspired by an [animation](http://blog.ninapaley.com/2013/05/04/morphing-tiles/) by Nina Paley

Also a step-by-step tutorial for doing the same animation using the Canvas, which should work better in Firefox.

* Step 1: set up canvas and draw a triangle, this will eventually be our clipping region
* Step 2: draw some more triangles, which we'll rotate later
* Step 3: rotate all but the clip triangle to a different start position
* Step 4: apply clipping
* Step 5: animate rotation with clipping
* Step 6: animate rotation without clipping to see what is going on
* Step 7: draw to an offscreen canvas to mirror the clipped triangle
* Step 8: add rotation and mirroring to get the first 1/4 tile
* Step 9: mirror to get 1/2 tile
* Step 10: mirror to get full tile
* Step 11: tile the full page with repeating images
