# Wheel

This file documents how I created the wheel part in Onshape. The part studio I used can be found [here.](https://cvilleschools.onshape.com/documents/44d11c822fc5279efa47b295/w/90300413fc4f16957eadc67b/e/3c0210e8dc1e0fa13d604cdf)

### Wheel Sketch

The first sketch adds on to the sketch of the tire which was created using [these instructions.]("/caster/parts/tire/README.md") First, you create an outline of the sketch on one side, then you mirror that outline across the vertical construction line. Finally, you add in the dimensions, so the sketch is fully constrained, and revolve the sketch around the horizontal construction line.

<img src="/caster/parts/wheel/images/wheel_sketch.png" width="600px" height="360px" alt="Main Wheel Sketch">

### Spoke Holes

This next sketch is created on one of the large faces of the wheel. Each arc and line is coincident with the origin, and the sketch is symmetrical about the vertical construction line. When the sketch is finished, it is extruded through the wheel, and filleted 2mm on each of the four inside edges. A circular pattern around the wheel creates the other four of the five holes.

<img src="/caster/parts/wheel/images/spoke_cut_sketch.png" width="600px" height="360px" alt="Spoke Hole Sketch">

### Complete

The final step is filleting the large face of each side of the wheel by 1mm. When you're done the wheel should look like this:

<img src="/caster/images/wheel.png" width="600px" height="360px" alt="Caster Wheel">
