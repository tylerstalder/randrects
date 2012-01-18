The Problem:

Write an IPhone or IPad app that draws an arbitrary set of rectangles,
using as few line segments as possible.

If any two rectangles share any part of an edge, these edges should be
drawn with a single line segment.  For instance, if two rectangles have
the exact size and position, then only four line segments would be
required to draw them.

Details:
Each rectangle is described by its origin (x,y), width, and height on a
plane that is 20 coordinates wide (x) by 10 coordinates tall (y).
Create an app that:
Accepts the number of rectangles to be generated
Generates a random set of rectangles on the 20x10 surface
Draws the rectangles using as few lines segments as possible
Your solution should make it clear that you've correctly solved the
problem... up to you how to accomplish that!
Example:

Here's one possible set of input and output:
Number of rectangles to generate: 3
Rectangles Generated
0, 0, 10, 10
0, 10, 10, 10
11, 11, 9, 9
Minimum Lines: 9
What to deliver:

Please build the app as an Xcode project.  When you're done, just zip it
up and email it back.  For an example of how this is done, see
http://developer.apple.com/library/ios/samplecode/MyImagePicker/MyImagePicker.zip.

Alternatively, if you want to use github, you can just send back a link
to the public project that contains your solution. 
