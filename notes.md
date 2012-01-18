1. Draw a grid and set up coordinates
2. Draw lines
3. Draw rectangles
4. Draw example rectangles
5. Draw random rectangles
6. Optimize rectangle drawing to save lines
7. Compute lines saved

Optimization
Keep an index of lines by using a string of coordinates as a key.
Poll the coordinate plane before drawing a line.
Stack the rectangles so that each is computed before drawing to grid.

Questions
Should the example fit on the default grid?
Is it optimizing drawing lines or drawing points?
  Save points by not drawing intersecting regions.
  Save lines by not drawing overlapping lines.
  Save lines by extending continuous lines.
Does each rectangle know about the others?
  Should a rectangle optimize itself and adjacents by points or lines?
  Is a rectangle a array of coordinates or an array of lines?

