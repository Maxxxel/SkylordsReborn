# Style Guide for Battleforge Models #
## Blender Settings ##
To make Blender models look like ingame models you need to change some settings within material properties (yes all zero) and world properties:  
![Blender Settings](https://i.gyazo.com/13f01c51e194881fb50a3cc4bfd0147a.png)
![World Settings](https://i.gyazo.com/9d67b83cd66816becd2c583ee31e04f7.png)  
Furthermore i provide you a basic Lighting as .glb file you can add to see shadows and such (you dont need to remove it on export, it wont be imported anyway) ![Download](https://github.com/Maxxxel/SkylordsReborn/raw/master/tutorial/Environment.glb)
## Texture Types ##
- File Type: DDS (BC3 Linear, DXT5)
- Are existing textures upscaleable? YES, but the resulting ingames are not as great as you may wish...
### Base Color Map ###
This map is the basic UV used for the models texture.
- Size: Unlimited (be careful)
- Notes: -
- Example:  
![Base Color Map](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Base%20Color%20Map%202.png)
### Normal Map ###
This map is used for Lighting.
- Size: Usually low res (512 x 512), but there's no limit
- Notes: Without the normal map the Model looks weird ingame.
- Example:  
![Normal Map](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Normal%20Map%202.png)
### Parameter Map
This map is used for fluid Textures. Only the areas that aren't black are colored by the Fluid Map.
- Size: Usually low res (512 x 512), but there's no limit
- Notes: I need to find out what else this is used for as some models have this but not fluid
- Example:  
![Parameter Map 2](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Parameter%20Map%202.png)
### Environment Map ###
This map makes no sense at all. Dont care for this!
### Refraction Parameter Map ###
This map is used for transparency effects.
- Size: Usually low res (512 x 512), but there's no limit
- Notes: If the map is all black, the material is transparent as well. See Examples for the effect with/without transparency. I dont know yet why there are 100% transparent ones included with some files, makes no sense.
- The Settings for this can be set within the Skylords Reborn Suite (see [Refractions InDepth](RefractionsInDepth.md))
- Example:  
<img src="https://i.gyazo.com/c0084f1555d54dac6d24da96f596291a.png" width="400"><img src="https://i.gyazo.com/c372552e42ed180e1e072d18a4c98eb6.png" width="423">
### Distortion Parameter Map ###
This map is unused!
### Scratch Map ###
Haven't found a usecase yet...
### Fluid Map ###
This map is used for animated textures, like flowing lava or water.
- Size: Usually low res, but there's no limit
- Notes: This doesen't need to apply to the whole texture. If this Map is small like the example underneath, it will be repeatedly placed in the areas marked by Parameter Map.
- The Settings for this can be set within the Skylords Reborn Suite (see [Fluids InDepth](FluidsTutorial.md))
- Example:  
![Fluid Map](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Fluid%20Map.png)
- Result:  
<img src="https://i.gyazo.com/1e12c3a1be18b0956a7cb9d23f318436.gif" width="250">
- Time for some Rainbow Candy:  
<img src="https://github.com/Maxxxel/SkylordsReborn/raw/master/tutorial/images/34ac46779e4b50d6fd29e7b1879c3cb6.gif" width="400">

## Texture Settings ##
Every mesh in Battleforge has it's own settings for several styling parameters. E. g. smoothness, metalness, etc. They can be set in two ways. Either from the Skylords Reborn Suite or from within Blender (recommended). A list of these parameters and what they do follows now.
### Refraction Color ###
No Effect yet...
### Smoothness ###
No Effect yet...
### Metalness ###
No Effect yet...
### Reflectivity ###
No Effect yet...
### Emissivity ###
No Effect yet...
### Refraction Scale ###
No Effect yet...
### Distortion Mesh Scale ###
No Effect yet...
### Scratch ###
No Effect yet...
### Specular Scale ###
- Type: float
- Default: 1.5 ==> a bit shiny
- The specular scale adds some shininess to the model
- How to change in Blender: unfortunately i haven't found a way yet. Means this value needs to be set with the Skylords Reborn Suite and tested ingame.
- Examples: left 10.0 vs. right 0.0  
<img src="https://i.gyazo.com/abf24e50339bbb1e344ba837e7293a5b.png" width=400><img src="https://i.gyazo.com/06273c8da433cfbc7cd80da79f02988e.png" width=369.5>  
### Wind Response ###
No Effect yet...
### Wind Height ###
No Effect yet...
### Depth Write Threshold ###
No Effect yet...
### Level of Detail ###
No Effect yet...
