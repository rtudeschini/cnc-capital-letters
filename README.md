# cnc-capital-letters
Capital Letters in AutoCAD Interchange format
By Rodrigo Tudeschini
tudeschini@gmail.com

---------------------------------------------

These files contains the alphabet, numbers and some characters in DXF format, with dimensions 300 x 500mm, wich can be used for CNC purposes.

You can navigate in the DXF file with a text editor, and you will find the drawing sintax in the end of the file, in the ENTITIES section.

In the DXF files, the properties are identified with numbers, as following:
0: Type of entity
5: Name of the instance
1n: X coordinate of the n-th point
2n: Y coordinate of the n-th point
3n: Z coordinate of the n-th point
40: Radius of the arc
50: Initial angle of the arc
51: Final angle of the arc

In the case of an arc, the properties 10, 20 and 30 indicate the center of the arc.

To form the letters, I used only the LINE and ARC entities. Please ignore the other entries.

The Ex file is an example of how the DXF files are structured. If you do not have an DXF viewer, open the Ex.png file to have an idea of the format of the generated drawing. 
