# IA Planning
### Tynan Purdy IB Math HL IA on Tessellations
## Why Tessellation
I wanted to research tessellations because I use them in robotics when designing a cut pattern to reduce weight in a sheet metal part without impeding on the structural rigidity of the part. Essentially what I am doing is cutting out a tessellation pattern in the sheet. I want to understand how these patterns work and how to represent and generate them mathematically. I can demonstrate the method of generating and using tessellation patterns in a javascript program and in SolidWorks with CAD models of sheet metal parts that have a tessellated lightening pattern. As with the EE, I don't actually know how to program in javascript, but with the assistance of the great and powerful internet (and Simon) I shouldn't have too hard a time figuring it out as I go. 

## Intro to Tessellation

Tessellations are when a shape is duplicated into a pattern with no gaps anywhere on the surface. There are 3 regular tessellation that use a single polygon: hexagons, squares, and triangles. Tessellation patterns are identified by the number of sides the polygon has and the number of lines intersecting at any vertex in the format of a Schlafli symbol. A pattern of hexagons would be indicated by {6,3} becasue it has six sides and every vertex is intersected by 3 lines. For a pattern of squares it would be {4,4}, and so on.

![alt text](http://mathworld.wolfram.com/images/eps-gif/RegularTessellations_1000.gif "Regular Tessellations")

Schlafli symbols are used to describe n dimensional polytopes as well, such as 3 dimensional tessellations. A dodecahedron is {5,3}, a cube {4,3}. All of the dice used in board games are 3 dimensional tessellations, as well as most all prisms. D4 = {3,3}. D6 = {4,4}. D8 = {3,4}. D12 = {5,3}. D20 = {3,5}. D10 uses a semiregular tessellation of equilateral triangles and a decagon. I could certainly render all of these dice with the program I write to display the tessellations. 

There are, of course, not just tessellations of one shape. There are semiregular tessellations which have a pattern of two polygons. These semiregular patterns are also known as Archimedean tessellations. Demiregular tessellations have 3 different polygons. 

Beyond even tessellations with multiple polygons, or 3 dimensional tessellations, you can also make tesselated patterns in the hyperbolic plane! Programming hyperbolic tessellations would be pretty complicated, but not nearly as complicated as actually representing the hyperbolic plane, so I would have to use a js library for the graphing. This would not impede on me personally doing the work of the math involved in the tessellation, and then not be malpractice to use a library in this demonstrative scenario. 