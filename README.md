Example mod to create a terrain texture mod for Embark (https://store.steampowered.com/app/1055090/Embark/).
More help at main example mod: https://github.com/lxteo/EmbarkExampleMod
Join our Discord if you have any questions! https://discord.gg/cbUNUVk

# ModInfo.xml

This must be included in every mod with name and description tags. Place it, and any other files inside %userprofile%\appdata\locallow\embark\embark\mods\(your mod name) folder. You may include an image file named screenshot.jpg/png inside to be used as the steam workshop preview image. You should then see your mod inside the mod panel when you run Embark. Use that to upload your mod to the Steam workshop when you are happy with your mod.

# Terrain Texture Mod

Simply change the image files of the terrain you want. Your mod needs to include all the textures even if you do not change some of them.

Naming convention needs to be followed, all textures need to be inside a folder in a Textures folder of the name "(MaterialId) (MaterialName)". The material name is not important but is helpful to keep things organized.

Textures should be in jpeg or png format and be 512x512 in size for full resolution. Smaller textures are also supported and will be automatically scaled. The file names should end with " albedo", " normal", " occlusion", or " specular".

Textures will be loaded only once when the game is first run. You will have to restart the game to view any changes made. Make sure your mod is enabled in the mods panel.
