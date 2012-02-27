#gh-svg

---

__gh-svg__ is a plugin for exporting [svg](http://www.w3.org/Graphics/SVG/) data from the [Grasshopper](http://grasshopper3d.com) and
[Rhino](http://www.rhino3d.com/) 3D modeling environments. The intent is work towards create greater
interoperability between different geometry editing softwares using open-source data
format standards, as well as making it easier to create dynamic interfaces
for topics that rely heavily on illustration and geometry, such as architecture,
urban design, industrial design, and data visualization.


Here's an [example](http://benjamingolder.com/static/files/dynamic_example.html).


## The Current State of this Software

_Fabruary 27th, 2012 ---_ I've now created some simple Dot and Polyline export
examples. They are a little slow, but they work fine.

_February 5th, 2012 ---_ I just made this repository for the project, and expect to
develop the plugin over the next several months. If you are interested in this
project, please 'watch' it here on Github.


## Next Steps to Development

* Point/Dot Export (Done!)
* Polylines Export (Done!)
* Viewport Projection (Done for points and polylines)
* Embedding arbitrary attributes
* Viewport Selection
* Curve Export

## But why?

Here’s why I think SVG is a good file format to export to:

1. SVG can be read by any common browser, and therefore there is no need for special software to view it.
2. SVG can be easily read and edited by most vector editing software, including Adobe Illustrator and many open source softwares.
style information can be easily embedded in the geometry, or can be adjusted with a style sheet
3. SVG is dynamic. This means I can create geometry with Rhino with embedded hypertext links, or I can use Javascript to display information when someone hovers their mouse over the geometry.

