# Caster

This is the project folder for the Caster assignment. This README is my engineering notebook for the caster.

The Onshape document which I'm working on can be found [here.](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/28092cdd77be910dc765f2cd)

## Table of Contents
* [Base](#base)
* [Mount](#mount)
* [Fork](#fork)
* [Tire](#tire)
* [Wheel](#wheel)
* [AxleCollarBearings](#AxleCollarBearings)


## Base

### Description

The base is the first assignment in the caster. It's a 120x200mm rectangle with six 10mm wide holes patterned in two directions, and evenly spaced throughout.

### Evidence

[Part Studio containing my Base part](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/28092cdd77be910dc765f2cd)

### Image

<img src="/caster/images/base.png" width="600px" height="360px" alt="Caster Base">

### Reflection

This first Onshape part was easy to make thanks to the [Onshape Fundamentals Course](https://learn.onshape.com/learn/learning-path/onshape-fundamentals-cad), and 
the detailed instructions in the assignment.



## Mount

### Description

The second part of the caster is the mount. It's a 120mm square which shares most of the geometry of the base. 

### Evidence

[Part Studio containing my Mount part](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/28092cdd77be910dc765f2cd)

### Image

<img src="/caster/images/mount.png" width="600px" height="360px" alt="Caster Mount">

### Reflection

Because the mount shares the geometry of the base, I made the two parts in the same Part Studio. This feature greatly reduced the time I had to put into the part, 
because I only had to add one line and one new extrusion. Multi-part part studios are simply amazing.



## Fork

### Description

The third part of the caster is the fork, a considerably more complex part than the first two. The fork consists of a circular base 80mm in diameter, two prongs 
which are 80mm long and filleted down 15mm, and a 60mm long cylindrical stem. 

### Evidence

[Part Studio containing my Fork part](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/193e1eacaf17ddfab84b5875)

### Image

<img src="/caster/images/fork.png" width="600px" height="360px" alt="Caster Fork">

### Reflection

The fork was slightly more complicated, but still not a challenge with the simplicity of Onshape. The hardest part for me was remembering where to find the 
functions which don't command the honor of being designated a keyboard shortcut.



## Tire

### Description

The next part in the caster is the tire, which is 15mmx20mm at its largest point and has angled sides. It's revolved 360° around a horizontal construction line, 
and filleted down 8mm on the outer edges.

### Evidence

[Part Studio containing my Tire part](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/3c0210e8dc1e0fa13d604cdf)

### Image

<img src="/caster/images/tire.png" width="600px" height="360px" alt="Caster Tire">

### Reflection

This was a very satisfyingly simple part to make. It's fun to see how easily you can turn a simple sketch into a tire with just the revolve function. One thing I 
was slightly disappointed about was that there was no keyboard shortcut for revolving. However, in my searching for said keyboard shortcut, I found a really 
trippy function which shows the curvature of a shape. It's called **Curvature Visualization**, and you can find it under **Camera and Render options** in the top 
right corner. Here is a picture of the tire with the option turned on:

<img src="/caster/images/curvature_visual.png" width="400px" height="240px" alt="Trippy Picture">



## Wheel

### Description

The Wheel is the fifth part of the caster. I built it in the same part studio as the tire since the two parts share some key geometry. The base sketch of the 
wheel looks like the letter **I**, and is 35mmx20mm. That base sketch is revolved 360°, and has five spoke holes cut patterned on the large face of the wheel.

### Evidence

[Part Studio containing my Wheel part](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/3c0210e8dc1e0fa13d604cdf)

### Image

<img src="/caster/images/wheel.png" width="600px" height="360px" alt="Caster Wheel">

### Reflection

The Wheel was the most complex part of the caster so far, and apart from a small hiccup regarding a fillet size, I encountered no problems. In the main I-shaped 
sketch, I tried using 6 lines mirrored over the vertical construction line instead of using 3 rectangles. I think that using this approach was more efficient in 
my situation where I was building the wheel in the same sketch as the tire, and it still produced the desired result.


## AxleCollarBearings

### Description

The final few parts were all in one assignment, and I made them in an assortment of part studios so that I could best take advantage of existing geometry. The 
descriptions for the small parts are as follows:
* Axle -- 60mm long tube which is 10mm in diameter, and has a flat bit on either end.
* Collar -- 10mm long hollow cylinder which has a diameter of 10mm, and a 3mm hole in the side.
* Bearing -- A 25mm circle with a width of 10mm, which is extruded 5mm.
* Washer -- Technically another bearing, it's a 25mm circle which is extruded 5mm, and has a width of 5mm.

### Evidence

[Part Studio with Axle and Collar](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/4a3403c658c5d2226fc0abb4)

[Part Studio with Bearing](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/3c0210e8dc1e0fa13d604cdf)

[Part Studio with Washer/Second Bearing](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/b4eec7aa4b944c1d3250ee23)

### Image

<img src="/caster/images/axle_collar_bearings.png" width="600px" height="360px" alt="Caster Small Parts">

### Reflection

These parts were quite simple, but I still learned some things in the process.
1. The **Use Function** is a feature that I found was very useful for creating sketches which relied on existing geometry. The function has an extremely intuitive 
keybinding of "**U**".
2. I learned how to compile multiple images into a single image using GIMP. I found [this stackexchange answer](https://graphicdesign.stackexchange.com/a/122304) 
to be very helpful as a guide.
