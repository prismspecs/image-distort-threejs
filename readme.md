# Usage:

1. edit ```inputImage```
2. launch it in browser
3. hit S key at any time to start
4. hit S key at any time to stop
5. it will spit out a .tar containing images, extract and navigate to that folder in terminal
6. ```ffmpeg -framerate 60 -pattern_type glob -i '*.jpg' -c:v libx264 -pix_fmt yuv420p _0ut.mp4``` for example
