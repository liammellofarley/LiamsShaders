# LiamsShaders
Film Style Shaders for OpenMW

Includes a Multi-Lut shader that can apply 2 LUTs at the same time with magnitude control, a simple Halation shader, and a simple chromatic aberration shader. 

Includes 40 LUTs, 20 set to Lut 1, 20 set to Lut 2. The image files contain 20 LUTs each and are 86x86x86. If you want to use two LUTs from the Lut1 Image just copy that one over the Lut2. 
The lut shader contains an interior and exterior version as I found it hard to get 1 light that looked nice in both interiors and exteriors. 

The halation and chromatic aberration shaders have a variety of settings to tweak, the defaults are probably high for regular gameplay and more intended to take film-style screenshots.

# Installation:
Just add the LiamsShaders folder to your OpenMW paths. I recommend using the chromatic aberration shader, halation shader, and multi-lut in that order as the last shaders you load, but as long as its after any SSAO and clouds/mist shaders etc. it should be fine.

# Screenshots
![Screenshot](sc2/image.png?raw=true "Title")
![Screenshot](sc2/screenshot023.png?raw=true "Title")
![Screenshot](sc2/screenshot031.png?raw=true "Title")
