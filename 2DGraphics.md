# 2D Graphics
* Vector vs raster
* Coordinate system

## Vector vs Raster
### Vector
* Ex drawing with a pen

### Raster
* Rectilinear pixels
* Draw with vector render as raster

## Rasterization
* Primitives - vertices
* Strokes - lines, curves
* Fill - region enclosed by strokes
* Vector is translated to a rectangular array of pixels
* Inevitably aliasing occurs when vector is translated to pixels

## Canvas Coordinates
* Arbitrary drawing coordinates

## Hierarchical Coordinate Systems
* Canvas-in-a-canvas
* Outer canvas for entire visualization
* Sub-canvas for data region

## Screen coordinates
* Specific to raster graphics
* Sometimes (0,0) is on the top left
* Starts from 0 and goes to V-RES or H-RES

## Canvas to Screen transformation
* Draw in canvas coordinates and translate to screen coordinates

## Summary
* Vector - shapes with vertices, strokes and fills
* Raster - shapes with a table of pixels
* Screen and canvas coordinates can be different
* Canvas can contain a canvas - hierarchy of coordinate systems