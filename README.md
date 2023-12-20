# tile-texture
Create a Tileable texture using AI

## How it should work
- Accept input image from user
- Crop input image into a square
- downsample to 512 x 512
- Offset image by 50% in both dimensions
- create mask with width of user input
- send to requested model

### Stretch Goals
- Add support for locally hosted stable diffusion (Is that even a thing?)
- Dall-e Support