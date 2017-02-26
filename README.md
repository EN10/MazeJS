#Maze#

Investigation in to Maze solving in JS
-

index.html loads tiny.png 10x10 pixel maze  

canvas set to image size    
zoom image to fit window height   
getImageData doesn't work after scale hence draw before and after scale    

getImageData produces a RGBA array  
black is 0,0,0,255 and white is 255,255,255,255   
RGB are the same so only Red is read    
RGBA means length / 4 and i*4   

pixels2Console() = pixels2Array() & array2Console()   

References
-

https://preview.c9users.io/en10/maze/index.html

https://www.youtube.com/watch?v=rop0W4QDOUI

https://github.com/mikepound/mazesolving

https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Pixel_manipulation_with_canvas