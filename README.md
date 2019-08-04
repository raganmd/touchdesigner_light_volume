# TouchDesigner Light Volumes

## Contributors 
**Author**  | [Michael Walczyk](http://www.michaelwalczyk.com)
**Adapted by** |  [Matthew Ragan](https://matthewragan.com)

## Platform
* [TouchDesigner 099](https://www.derivative.ca/099/Downloads/)

Light Volumnes is a simple shader intended to help create the illusion of faux lighing volumns, similar to what you'd see in haze. This implimentation is a 2D post process effect achieved in a shader. Controls for this tox are exposed as Custom Parameters.

## Features and Parameters
### Textures
Parameter | Description and Function
---|---
Volume Color | The color image to be used for generating the faux volume
Scene | This represents your rendered scene. This could be created using only TOPs, or it could be a 3D rendered scene  
Light Source | This should be an image where the light sources are represeted as all white textures.
### Volume Settings
Parameter | Description and Function
---|---
Light Position | The UV position of your light source in UV space. 
Decay | The roll-off of the light over distance.
Weight | The strength / brigntess of lighting accumulation 
Density | The accumulation range and direction. Positive values come "towards" the viewport, negative values move away
Exposure | Exposure control before output - a brightness dial. 
Samples | The number of steps in the ray-marching process. 