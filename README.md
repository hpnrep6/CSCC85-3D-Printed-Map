# CSCC85 Map STL Files for 3D Printing

## Files included:

- Building files (named #.stl)
- Road files (named a#.stl)
- Pin file (0pin.stl) to attach everything together
- Blender mode file
- Sample Orca Slicer project files for reference

## Printer requirements

The STL files are split to work on a printer that can print 4 materials in one print, such as a Bambu Lab A1 mini (that was used to print the original).

## Print instructions

Print all building and road files, and as many pins as needed.

Refer to map.blend for the colouring of prints.

To reduce the number of colour changes and to hold the different coloured pieces together, you will need to ensure that after a layer height of around ~1.2mm, the rest is printed in the same colour. This can be done using material painting in your slicer. The original had a constant colour starting from layer 5.

When colouring, use "split to parts" for the stl files in your slicer. You may need to manually material paint some parts and there are some gaps in between different colours so you will either need to manually fix the mesh in Blender or in your slicer add a shape to fill in the gap.

### Print parameters used in the original

- 0.24mm first layer height
- 0.32mm every other layer height
- 2 perimeters
- 5% grid infill
- 4 bottom layers and 4 top layers

## Reference photos

![PXL_20241023_170257744](https://github.com/user-attachments/assets/a14b4570-d2f5-473f-b598-51849346862c)
![PXL_20241023_170311664](https://github.com/user-attachments/assets/39473a94-e6a1-49d0-98b1-9eda2494484d)
