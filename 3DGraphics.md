# 3D Graphics
* Project the 2d version of the object onto a screen

## Polygonal Model
* Vector primitives - triangles
* Region inside triangle is a polygonal face
* Projected onto a 2D plane
* 2D plane is discretized/rasterized
* Process-for each primitive (triangle)
	* Compute illumination
	* Project to image plane
	* Fill in pixels (rasterize)
	* Pixel processing - coloring

## Viewing a 3D scene
* World coordinate system
* Eye point
* Lookat point
* Translation from world coordinate system to canvas coordinates

## Perspective distortion
* Farther away smaller; closer the larger