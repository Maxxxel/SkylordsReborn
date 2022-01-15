# Style Guide for Battleforge Models #

## Texture Types ##

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
### Refraction Parameter Map ###
### Distortion Parameter Map ###
### Scratch Map ###
This map is used for ...
- Size: Usually low res (512 x 512), but there's no limit
- Notes: I dont know yet what effect it has
- Example:  
![Scratch Map 1](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Scratch%20Map.png)
### Fluid Map ###
This map is used for animated textures, like flowing lava or water.
- Size: Usually low res, but there's no limit
- Notes: This doesen't need to apply to the whole texture. If this Map is small like the example underneath, it will be repeatedly placed in the areas marked by Parameter Map.
- The Settings for this can be set within the Skylords Reborn Suite (see [Fluids InDepth](FluidsTutorial.md))
- Example:  
![Fluid Map](https://raw.githubusercontent.com/Maxxxel/SkylordsReborn/master/tutorial/images/Fluid%20Map.png)
- Result:  
![Fluid Map Animation](https://i.gyazo.com/1e12c3a1be18b0956a7cb9d23f318436.gif)
