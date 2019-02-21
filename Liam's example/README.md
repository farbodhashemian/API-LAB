<<<<<<< HEAD
This example uses the "css3d_molecules" example from the three.js library.

The initial plan was to add a control menu (called dat GUI), the menu was supposed to have options that contain different groups of molecules (Alkanes, Alkenes, Alcohols...). However, after trying for some time, the menu seemed to be hard to add as it interfered with the code of the example. Therefore, I decided to make a vertical list of the molecules and add molecules that have recognizable geometrical shapes. The aim of that is to show the clear correlation between geometry and chemistry, as well as adding an artistic feel of the molecules. 

Designers have the chance of expressing such complicated and foreign subject in an interesting and artistic way, using simplified JS libraries such as three.js.

I could find a very big data bases with a lot of chemical molecules' structures, in the same format that the example is using (pdb). Though, as I decided to use a customized geometrical molecules, I had to find something else. That is when I found https://www.mn-am.com/online_demos/corina_demo_interactive , which enabled me to make my own chemical molecules anf export them as pdb files that I could use in my example. 

Adding the molecule was very easy, I had to place them in the folder "molecules/models", then add them to my JSON object MOLECULES. Making vertical lists and changing background color and bonds color was done in CSS. There is a possibility to change the shape of the atoms by replacing ball.png to any of the other shapes in the "sprites" file.
=======


