<!-- 

Auto Generated File DO NOT EDIT 

-->

# Cairo Circuit Map

_Requires Cairo to be installed_

Shows a simple plot of the path, but no map behind it...


```xml
<component type="cairo_circuit_map" size="256" />
```
<kbd>![06-cairo-circuit-map-0.png](06-cairo-circuit-map-0.png)</kbd>



# Colours

You can change the colours with

`fill`, `outline` for the path, and `loc_fill`, `loc_outline` for the "location" dot.


```xml
<component type="cairo_circuit_map" size="256" fill="255,255,0" outline="255,0,255" />
```
<kbd>![06-cairo-circuit-map-1.png](06-cairo-circuit-map-1.png)</kbd>




```xml
<component type="cairo_circuit_map" size="256" loc_fill="255,255,0" loc_outline="255,0,255" />
```
<kbd>![06-cairo-circuit-map-2.png](06-cairo-circuit-map-2.png)</kbd>



# Line width

You can change the line widths with `line_width` and `loc_size` - The numbers are relative to the size of the overall widget, so `1` 
means a line that is the whole width of the widget.

The map will be simplified to reduce the number of points as the line width increases.



```xml
<component type="cairo_circuit_map" size="256" line_width="0.05" loc_size="0.05" />
```
<kbd>![06-cairo-circuit-map-3.png](06-cairo-circuit-map-3.png)</kbd>

