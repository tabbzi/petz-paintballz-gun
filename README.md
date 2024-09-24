# petz-paintballz-gun
Web app using HTML5 + Java to draw and export LNZ Paint Ballz

Load the [live demo](https://tabbzi.github.io/petz-paintballz-gun/) here!

## To-Do
- [ ]  Fix sizing inconsistencies
- [ ]  Add all the colors and corresponding hex colors for all games... or handle palettes better, somehow
- [ ]  Add a tracker to change order or delete circles manually
- [ ]  Add a palette that can be set up and then swapped through using tab or to specific options using numbers
- [ ]  Allow local image to be uploaded as background
- [ ]  Perfect parameters
- [ ]  Figure out why tattoos on PWS sometimes don't work due to NaN floating point error
- [ ]  Make labels on draw area more clear
- [ ]  Normalize load from LNZ to eliminate any roll / pitch / yaw transformations back to (0,0,1) (figure out that math)
- [ ]  Remove nonfunctional function for autopopulating dropdown with color map
- [ ]  Add documentation on how to use Paintballz Gun and warning to back up Paintballz often
- [ ]  Add a ico and splash image of a Catz with paintball scope
- [ ]  Clear Java for any vulerabilities before hosting on FTP
- [x]  Make helper sphere less confusing by projecting design onto it
- [x]  Add light mode / dark mode toggle
- [x]  Fix NaN floating point error when loading or outputting LNZ where normalized x, y, and z values all round (floor) to zero
- [x]  Change output to comma-delimited to be very explicit!
- [x]  Render fuzz on circles e.g. https://stackoverflow.com/questions/33907082/draw-squiggly-line-along-a-curve-in-javascript
- [x]  Render no outline when -1 and render left half-circle outline when -2 e.g. https://www.kirupa.com/html5/drawing_circles_canvas.htm
- [x]  Confirm roll yaw pitch values are correct relative to Petz
- [x]  Confirm buttons give correct roll yaw pitch values relative to Petz
- [x]  Enable scroll bar size changer
- [x]  Host live version on GitHub.io
- [x]  Remove extra rotation function
- [x]  Add a copy button
- [x]  Add a hover cursor circle to see where placing
- [x]  Add a delete circle functionality
- [x]  Add preset roll yaw pitch for centered on back top front right left bottom of ball with visual guide
- [x]  Allow comma-delimited LNZ input in addition to tab-delimited (or just remove commas from input)
- [x]  Move base ballz to global properties
- [x]  Remove transform that happens during initial draw (comment out see what it does)
- [x]  Add quick ref for Babyz base ballz too

## License

> [!NOTE]  
> This also means you are free to modify and embed this app into your own Petz website!

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org>