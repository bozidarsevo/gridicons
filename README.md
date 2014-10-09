# Gridicons

An experiment to collaboratively create a new consistent icon set. 


### Icon Guidelines

- 24dp base grid
- straight 45 degree angles
- flat, bidimensional look (no faux 3D whatsoever)
- 2dp lines
- 2dp radius rounded corners only when necessary
- no logos
- hollow means inactive, solid means active (for example a hollow bookmark star is solid when checked)

These are not rules, they are guidelines that can be broken in style. The purpose of them is to try an ensure a uniform look as we all work on it together. They are also open to growing organically.


### Making a new icon

1. Make sure your repo is fresh, then open gridicons.ai. 
2. Press Shift + O to open the Artboard manager. 
3. Now create a new artboard and position it where it makes sense. Name the artboard using lowercase letters and dashes.
4. Draw your icon. 


### Exporting

To export SVGs, do this:

1. In Illustrator pick "Save as Copy...", pick the SVG format and the filename "gridicons.svg" (it defaults to "gridicons copy.svg"). Now check "Use Artboards". 
2. Save to the "svg" folder and overwrite files. Files will be named "gridicons-[artboard].svg", for example "gridicons-calendar.svg".

### Clean up with Grunt

Make sure you have `grunt` and `grunt-svgstore` installed. 

In the commandline, type `grunt`. This will clean up and combine all the SVG icons into a single sprite in the `svg-set` directory, called `gridicons.svg`. 

@todo: Grunt should update the index.html example page with copy/paste instructions as well.


### Icon Font

In the deprecated folder there's a basic FontCustom template system bundled with this package. This will eventually be removed. 