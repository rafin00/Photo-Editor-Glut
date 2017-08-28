# Photo-Editor-Glut(C++)
Photo Editor Using Glut(C++)

P.S : 
1. Window size can not be resized(cause in Flaws(1) section). Always set to 700x500 in handleReshape() function.
2. To switch between functionalities press Right Mouse Button
3. Only loads BMP(24 bit) images
4. While loading some images of hign resulation(yts.bmp) you may need to Zoom in to see its full view as window resizing is turned off

Functionalities:
1. Right Click mouse button to switch between functionalities
2. Load from a set of Images
3. Rotate
4. Flip
5. Brightness Adjustment
6. Contrast Adjustment
7. Zoom in/out(scale)
8. Draw using pencil
7. Draw objects(lines,rectangles,line strips) by hold and press mouse buttons just like in ms paint
8. Change colors while drawing from mouse right button menu
9. Grayscale to Color and vice-versa convertion

Flaws :
1. When the window is resized the mouse con-ordinates do not match with the texture co-ordinate hence resizing is set off
2. While doing Brightness and color adjustments some parts of the image gets burned
3. Save Image function doesn't work
4. Some BMP(24bit) images like the yts image("yts.bmp") Doesn't show its original colors in the window
