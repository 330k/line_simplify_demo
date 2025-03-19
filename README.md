# line_simplify_demo

A Comparison of Line Simplification Algorithms

https://330k.github.io/line_simplify_demo/gpx_visual_simplify.html

## Algorithms

* (Ramor-)Douglas-Peucker
  * A Top-Down approarch that minimize maximum perpendicular distance
  * https://en.wikipedia.org/wiki/Ramer%E2%80%93Douglas%E2%80%93Peucker_algorithm
* Visvalingam-Whyatt
  * A Bottom-Up approach that eliminates the point with minimum adjacent triangle area
  * https://en.wikipedia.org/wiki/Visvalingam%E2%80%93Whyatt_algorithm
* Reumann-Witkam
  * https://psimpl.sourceforge.net/reumann-witkam.html
* Lang
  * https://psimpl.sourceforge.net/lang.html
* Cross-Track
  * A Bottom-Up approach that eliminates the point with minimum perpendicular distance 
  * https://www.gpsbabel.org/htmldoc-development/filter_simplify.html
* Arc-Length
  * A Bottom-Up approach that eliminates the point with minimum geodesic distance decrease
  * https://www.gpsbabel.org/htmldoc-development/filter_simplify.html
* Largest Triangle Three Buckets
  * https://dev.to/crate/advanced-downsampling-with-the-lttb-algorithm-3okh
* Kashimir3D-Emulate
  * A Bottom-Up approach that eliminates the point with minimum distance
  * This is not a perfect emulation of Kashmir3D (Kashmir3D's algorithm is somehow differenct from [release note](https://www.kashmir3d.com/kash/kashnews.html#894))
* Nth-Point
  * Simply keep n-th points
  * https://psimpl.sourceforge.net/nth-point.html 
