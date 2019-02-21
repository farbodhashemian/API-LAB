This example is based on Modifier Tessellation, an example from the three.js library.
Link to original example: https://threejs.org/examples/#webgl_modifier_tessellation

It shows a text that is floating on the screen and it's 3D letters disperse and recollect.

The code creates faces (faces are three lines connected/triangles) which form the 3D letters.

A collection of faces is Geometry, and it is in THREE.TextGeometry that I have modified:
Size, Height, curveSegments, bevelThickness and bevelSize.

I have also modified camera-angles, removed stats and changed the text that's displayed.

Finally, I added a CSS file with a linear gradient background. 
To do this I had to make the background transparent in the html file. 
