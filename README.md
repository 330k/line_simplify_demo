# line_simplify_demo

A Comparison of Line Simplification Algorithms

https://330k.github.io/line_simplify_demo/gpx_visual_simplify.html

## Algorithms

* (Ramor-)Douglas-Peucker
  * A Top-Down approarch that minimize maximum perpendicular distance
  * https://psimpl.sourceforge.net/douglas-peucker.html
* Visvalingam-Whyatt
  * A Bottom-Up approach that eliminates the point with minimum adjacent triangle area
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
* Kashimir3D-Emulate
  * A Bottom-Up approach that eliminates the point with minimum distance
* Nth-Point
  * Simply keep n-th points
  * https://psimpl.sourceforge.net/nth-point.html 
