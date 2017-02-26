#Maze#

Investigation in to Maze solving in JS
-

index.html loads tiny.png 10x10 pixel maze  

zooms it to fit page    
getImageData doesn't work after scale hence draw before and after scale    

getImageData produces a rgba array  

black is 0,0,0,0 and white is 255,255,255,255   
as 4 subpixels are the same so only Red is looked at    
RGBA hence length / 4 and i*4

References
-

https://preview.c9users.io/en10/maze/index.html

https://www.youtube.com/watch?v=rop0W4QDOUI

https://github.com/mikepound/mazesolving

https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Pixel_manipulation_with_canvas